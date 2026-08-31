# Wan Animate — SAM3 Head Matchmove

ComfyUI workflow and reference outputs for the stable frozen-SAM3-mask pass.

- `workflows/`: editable ComfyUI workflow.
- `masks/`: original-size black/white SAM3 head mask MP4 used to freeze tracking.
- `renders/`: 640-square and 720-square Wan processing results composited back to the original frame size.

The frozen mask avoids the SAM3 tracker losing the head in later frames.
ComfyUI Wan Animate SAM3 head matchmove workflows and reference outputs
