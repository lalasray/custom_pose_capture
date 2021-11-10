# custom_pose_capture
Goal: Create 3D pose render from a single RGB Video file.
## Workflow:
Video->Detectorn(2D Coordinates.npy)->VideoPose3D(3d joints.npy)->(TODO)HRM/bvh_skeleton(.bvh)->(TODO)Blender(Render outut)
## 
## References
1. Detectron: https://github.com/facebookresearch/Detectron/
2. VideoPose3D: https://github.com/facebookresearch/VideoPose3D
3. bvh_skeleton: https://github.com/HW140701/VideoTo3dPoseAndBvh
4. HRM: https://github.com/Dene33/hmr/blob/master/csv_to_bvh.py
5. Render: https://github.com/Dene33/hmr/blob/master/csv_to_bvh.blend
