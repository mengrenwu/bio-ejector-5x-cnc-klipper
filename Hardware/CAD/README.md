# CAD

CAD models and mechanical drawings for the five-axis CNC system, organized by component type.

| Folder | Purpose |
| --- | --- |
| [Holders](Holders/README.md) | Holders, mounts, and fixtures for the CNC system and air ejector assembly. |
| [StructuralComponents](StructuralComponents/README.md) | Frames, brackets, base plates, and other structural parts. |
| [BeltDrivenLinearStages](BeltDrivenLinearStages/README.md) | Belt-driven linear motion assemblies and their components. |
| [LeadScrewStages](LeadScrewStages/README.md) | Lead screw-driven linear motion assemblies and their components. |

STL models are currently available in `Holders/` and `LeadScrewStages/`. The other folders are reserved for future designs.

## Downloading Models

STL files are tracked with Git Large File Storage (Git LFS). With Git LFS installed, run these commands from the repository root to download the model files:

```sh
git lfs install --local
git lfs pull
```
