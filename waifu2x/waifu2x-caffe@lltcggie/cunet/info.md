**Note**: The input image is padded before further processing.

```python
## Super-Resolution

# scale2.0x_model
sr_args = dict(up_scale=2, is_rgb_model=True, pad=None, crop=None, pre_upscale=False)

# noise0_scale2.0x_model
sr_args = dict(up_scale=2, is_rgb_model=True, pad=None, crop=None, pre_upscale=False)

# noise1_scale2.0x_model
sr_args = dict(up_scale=2, is_rgb_model=True, pad=None, crop=None, pre_upscale=False)

# noise2_scale2.0x_model
sr_args = dict(up_scale=2, is_rgb_model=True, pad=None, crop=None, pre_upscale=False)

# noise3_scale2.0x_model
sr_args = dict(up_scale=2, is_rgb_model=True, pad=None, crop=None, pre_upscale=False)


## Denoising

# noise0_model
args = dict(up_scale=1, is_rgb_model=True, pad=None, crop=None, pre_upscale=False)

# noise1_model
args = dict(up_scale=1, is_rgb_model=True, pad=None, crop=None, pre_upscale=False)

# noise2_model
args = dict(up_scale=1, is_rgb_model=True, pad=None, crop=None, pre_upscale=False)

# noise3_model
args = dict(up_scale=1, is_rgb_model=True, pad=None, crop=None, pre_upscale=False)
```