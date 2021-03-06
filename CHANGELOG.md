# Change Log
All notable changes to this project will be documented in this file.

As we're at the 0.x phase, deprecations and breaking changes will still happen. They will be documented here.

Once we react 1.0 all deprecations will be removed and the project will switch to SemVer.

## Uncommitted

## 0.10.0 - 2019-09-10
### New updates
- `width` and `height` can now be omitted to force the component to 100% of the parent container
- `defaultWidth` and `defaultHeight` are added to specify a placeholder width/height for the initial render and server rendering
- `mouseEvents` and `touchEvents` can be used to enable/disable mouse and touch events completely
- `animateMaxScreens` specifies how far must a change to `center` be before we stop smoothly animating to it
- `twoFingerDrag` and `twoFingerDragWarning` can be used to block dragging the map with one finger
- `onAnimationStart` and `onAnimationEnd` callbacks notify us if the map is moving or not

### Breaking changes
- `zoomSnap` is now enabled by default
- `metaWheelZoom` replaces `zoomOnMouseWheel` and is reversed (previous `false` is now `true`)
- `metaWheelZoomWarning` replaces `mouseWheelMetaText`

### Other changes
- There have been numerous bug fixes since the `0.9` series, too many to mention all now

