# PyTorch AV Perception Guide

Visual learning reference for PyTorch concepts applied to autonomous vehicle perception. Images and diagrams stored here are referenced by Notion study documents.

## Structure

```
images/
├── concepts/      # Core PyTorch concepts (autograd, modules, tensors)
├── errors/        # Common errors with buggy→fixed code screenshots
├── training/      # Training loop diagrams, loss curves, scheduler plots
├── architecture/  # Model architecture diagrams (PointPillars, BEV, etc.)
```

## Linked Notion Pages

- PyTorch Comprehensive Interview Guide — AV Perception
- nuScenes PointPillars — Implementation & Experiments

## Topics Covered

- [x] Tensor fundamentals, reshaping, broadcasting
- [x] Autograd & computational graph
- [x] nn.Module, Parameters, Buffers
- [x] Dataset, DataLoader, custom collate_fn
- [x] Training loop, gradient accumulation, clipping
- [x] Loss functions (focal, SmoothL1, CE)
- [x] Conv2d, ConvTranspose2d, depthwise separable
- [x] GPU memory, AMP, gradient checkpointing
- [x] Debugging (anomaly detection, hooks, gradcheck)
- [x] Advanced (einsum, linalg.solve, DDP, ONNX)
- [ ] Transformers & attention (coming)
- [ ] Vision Transformers / ViT (coming)
