# lights-detection project
MIT license

## Model file
- checkpoint.pth: A trained torch checkpoint file for traffic lights.

## How to used
```
    checkpoint = torch.load('checkpoint.pth', map_location=device,weights_only=False)
    model.load_state_dict(checkpoint['model_state_dict'])
    model.eval()
```
