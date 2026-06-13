# Changelog

## 1.0.0 (2026-06-13)


### Features

* add mesh highlight on selection (TreeView -&gt; ViewModel -&gt; GL render) ([abcfcee](https://github.com/CrisM6285/UnBox3D/commit/abcfcee9800c369509331508112e1c6a8467584e))
* fix ring hover gaps and add gizmo element highlight on hover ([afc8939](https://github.com/CrisM6285/UnBox3D/commit/afc8939880d54cba1eb9b52ac5ac9d94de79fa78))
* mode-specific gizmo visuals + axis-constrained drag ([99080c2](https://github.com/CrisM6285/UnBox3D/commit/99080c268ac309bd2ea726e7da8ee0bd8715bcf7))
* mode-specific gizmo visuals + axis-constrained drag ([177d58c](https://github.com/CrisM6285/UnBox3D/commit/177d58c9f74c24a23b36f89dfb0add4000552581))
* **ruler:** add arrow and height drag ([5ab6baa](https://github.com/CrisM6285/UnBox3D/commit/5ab6baa01fbabf8ef47f81ff7f72454dfe716e2b))
* **ruler:** add Delete key to remove selected ruler ([5470b60](https://github.com/CrisM6285/UnBox3D/commit/5470b60239efca029ba4cf39a864f096badf8b5f))
* **ruler:** add floating measurement label with edit mode ([c870ac5](https://github.com/CrisM6285/UnBox3D/commit/c870ac5634db52249455348abe50a0d3b381f436))
* **ruler:** add ruler placement on grid click ([1b1c120](https://github.com/CrisM6285/UnBox3D/commit/1b1c1207a772281b302ef5efaa4f23e6296415c1))
* **ruler:** add ruler selection and base movement ([b4659ad](https://github.com/CrisM6285/UnBox3D/commit/b4659ad5f70a047ddc1f38ee4d326f6c6b270a10))
* **ruler:** add undo/redo for all ruler operations ([8223878](https://github.com/CrisM6285/UnBox3D/commit/8223878828c4528ed0d1ebb40b16847a41afb60f))
* **ruler:** ghost rulers and labels when not in ruler mode ([c449121](https://github.com/CrisM6285/UnBox3D/commit/c44912176ccce2124eeff0d6cf198a89b4da3699))
* **selection:** read mesh & highlight colors from settings with fall… ([d3794fb](https://github.com/CrisM6285/UnBox3D/commit/d3794fbadfbd10e25f4907780343416348d07b3a))
* **selection:** read mesh & highlight colors from settings with fallback ([21109c8](https://github.com/CrisM6285/UnBox3D/commit/21109c812065d2306d3f48fb46d0a9d464b02860))
* snap back, deselect, precise rotate/move/scale, scale & info panel, unit system, help window update, highlight fix ([7f5385f](https://github.com/CrisM6285/UnBox3D/commit/7f5385f8977eb777d5e912ff390e0810394d47d9))
* snap back, deselect, precise transforms, scale & info panel, unit system, highlight fix ([dce7a7d](https://github.com/CrisM6285/UnBox3D/commit/dce7a7d14d311cd7f3540231c043eeab4ebcb833))
* UI overhaul - toolbar rework, undo/redo, dark theme, notification system, panel animations ([2601317](https://github.com/CrisM6285/UnBox3D/commit/26013174588bdb038e8d56d929c19a3602107642))


### Bug Fixes

* grid fixed ([da7094c](https://github.com/CrisM6285/UnBox3D/commit/da7094c162290e0ccdd5196239790d2fabab596b))
* grid fixed, please work ([3da11c2](https://github.com/CrisM6285/UnBox3D/commit/3da11c2f7c6b483f3cf59e15704b6fab6a986d39))
* **logger:** append to log file instead of overwriting ([e5c47ee](https://github.com/CrisM6285/UnBox3D/commit/e5c47eed119cbf79784f7d3d09c849d0542a037a))
* prevent gizmo clicks from selecting/moving the wrong mesh ([3a490fd](https://github.com/CrisM6285/UnBox3D/commit/3a490fd7b7cd6adb43b610a0b55cab979675ae0b))
* RayCaster has been fixed to properly select the desired mesh in the 3D space. The biggest issue was that GetMousePosition() didn't actually get the screen coordinates and the fix was to use WinForms control. Also made modifications to scroll automatically to the item on the list when a mesh is selected with the mouse, however, it seems the scrolling only works when the mesh in the list is near wherever you are currently scrolled (MainWindow.xaml.cs). ([7bd79d9](https://github.com/CrisM6285/UnBox3D/commit/7bd79d9bf8064c2588ec0641820be59ed3cafb69))
* restore gizmo visibility after deselect and wire deselection in all states ([bcd3c58](https://github.com/CrisM6285/UnBox3D/commit/bcd3c5886320b943a28b12aa1b023ca5d4b8da3a))
* retarget gizmo when mesh selected from Meshes panel ([a4e94a9](https://github.com/CrisM6285/UnBox3D/commit/a4e94a91d1a6d2570bccc855c2349001d2b8a739))
* rotate mesh around its own center instead of world origin ([4056102](https://github.com/CrisM6285/UnBox3D/commit/40561026e8a264b7825e2a3dd6d7f71db4cceae1))
* **ruler:** cancel label edit on GL viewport click ([63e6c27](https://github.com/CrisM6285/UnBox3D/commit/63e6c27d25537214eaf86c21d53459973dc2141f))
* **ruler:** replace Popup with owned transparent Window for labels ([af0c064](https://github.com/CrisM6285/UnBox3D/commit/af0c06443640a2245396caa768301be4234399cc))
* snap gizmo back to mesh position on undo/redo ([c45fe73](https://github.com/CrisM6285/UnBox3D/commit/c45fe73387221d4c618c154cbcc40b28ef3dfacf))
* **unfolding:** fix SVG export path; improve Blender version config and default filename ([7d774f8](https://github.com/CrisM6285/UnBox3D/commit/7d774f8cff377aaff79db95d16ad733ae3530744))
