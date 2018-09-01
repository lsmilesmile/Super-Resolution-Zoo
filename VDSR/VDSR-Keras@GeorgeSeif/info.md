```python
# VDSR_2x
sr_args = dict(up_scale=2, is_rgb_model=False, pad=None, crop=None, pre_upscale=True, upscale_uv=False, resample_kernel='Catmull-Rom')

# VDSR_3x
sr_args = dict(up_scale=3, is_rgb_model=False, pad=None, crop=None, pre_upscale=True, upscale_uv=False, resample_kernel='Catmull-Rom')

# VDSR_4x
sr_args = dict(up_scale=4, is_rgb_model=False, pad=None, crop=None, pre_upscale=True, upscale_uv=False, resample_kernel='Catmull-Rom')
```