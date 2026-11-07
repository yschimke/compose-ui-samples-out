# Compose UI Samples — design artifacts

Importable sticker-sheet for **`org.jetbrains.compose.foundation:foundation`**, rendered from the committed
`@Preview` catalog in [`yschimke/compose-ui-samples`](https://github.com/yschimke/compose-ui-samples). This branch is a
**generated delivery artifact** — browse it in the page below, or pull it into
Figma / Stitch / Claude Design.

## 🔎 Browse the catalog

**[▶ Open the rendered catalog (htmlpreview)](https://htmlpreview.github.io/?https://github.com/yschimke/compose-ui-samples/blob/design-artifacts/compose-ui-samples/index.html)**

A self-contained gallery — one card per component with its rendered PNG,
dimensions, accessibility greenlines, and a link to an editable SVG wireframe.

## 🔬 Compare SVG vs PNG

**[▶ Open the SVG↔PNG comparison (htmlpreview)](https://htmlpreview.github.io/?https://github.com/yschimke/compose-ui-samples/blob/design-artifacts/compose-ui-samples/compare.html)**

Every component on one row: its editable **figma-svg** re-rasterized by the
browser beside the rendered **PNG** it is measured against — the design vector on
the left, the render on the right, as everywhere else the two are shown together
— plus a live **structural-similarity (SSIM)** match
score — so you can eyeball vector fidelity across the whole system at once and
spot which stickers drift. The score is pre-blurred and downscaled, so a
half-pixel rasterizer offset doesn't read as a mismatch.

## 🎛 Customise live

**[▶ Open this catalog in the live preview server](https://preview.coo.ee/compose-ui-samples/)**

The same rendered components, served live by `compose-preview serve --catalogs compose-ui-samples` —
open one, then change the theme, locale, font scale, or device and watch it
re-render. Every entry in `catalog.json` carries a per-variant `livePreview`
deep link to its exact preview on the same server, so browsing this branch and
customising the live render are two ends of one workflow.

## At a glance

| | |
| --- | --- |
| Components | **638** |
| Rendered images (PNG) | **1085** |
| Editable wireframes (SVG) | **567** |
| Editable design vectors (figma-svg) | **622** |
| Components with a11y greenlines | **111** |
| Library | `org.jetbrains.compose.foundation:foundation`<br>`androidx.compose.foundation:foundation`<br>`org.jetbrains.compose.foundation:foundation-layout`<br>`androidx.compose.foundation:foundation-layout`<br>`org.jetbrains.compose.ui:ui`<br>`androidx.compose.ui:ui`<br>`org.jetbrains.compose.ui:ui-graphics`<br>`androidx.compose.ui:ui-graphics`<br>`org.jetbrains.compose.ui:ui-text`<br>`androidx.compose.ui:ui-text`<br>`org.jetbrains.compose.ui:ui-unit`<br>`androidx.compose.ui:ui-unit`<br>`org.jetbrains.compose.animation:animation`<br>`androidx.compose.animation:animation`<br>`org.jetbrains.compose.animation:animation-core`<br>`androidx.compose.animation:animation-core`<br>`org.jetbrains.compose.animation:animation-graphics`<br>`androidx.compose.animation:animation-graphics`<br>`org.jetbrains.compose.runtime:runtime`<br>`androidx.compose.runtime:runtime`<br>`org.jetbrains.compose.runtime:runtime-saveable`<br>`androidx.compose.runtime:runtime-saveable`<br>`org.jetbrains.compose.material:material`<br>`androidx.compose.material:material` |
| Renderer | compose-preview 2.86.0 |
| Schema | `design-parity-catalog/v1` |
| Generated | 2026-11-07 |

## Components by group

| Group | Count |
| --- | ---: |
| FlexBox | 32 |
| BasicTextField | 19 |
| AnimatedVisibility | 19 |
| SizeModifier | 17 |
| Focus | 14 |
| Modifier | 14 |
| TextField | 13 |
| PolygonShape | 12 |
| SharedTransition | 11 |
| DragGestureDetector | 10 |
| LazyDsl | 10 |
| Pager | 10 |
| LazyGrid | 9 |
| Grid | 9 |
| Tab | 9 |
| AnchoredDraggable | 8 |
| FocusAwareInput | 8 |
| Transition (Animation Core) | 8 |
| LazyStaggeredGrid | 7 |
| Selection | 7 |
| AnnotatedStringBuilder | 7 |
| Chip | 7 |
| List | 7 |
| Style | 6 |
| ProgressiveBlur | 6 |
| FontFamily | 6 |
| RememberSaveable | 6 |
| SelectionControls | 6 |
| TransformGesture | 5 |
| FlowColumn | 5 |
| FlowRow | 5 |
| LayoutPadding | 5 |
| DrawScope | 5 |
| DrawText | 5 |
| AnimatedContent | 5 |
| Scaffold | 5 |
| Border | 4 |
| ContextMenu | 4 |
| KeyboardForm | 4 |
| KeyboardType | 4 |
| LazyLayout | 4 |
| Overscroll | 4 |
| Column | 4 |
| Intrinsic | 4 |
| LayoutOffset | 4 |
| AndroidView | 4 |
| DrawModifier | 4 |
| LayerModifier | 4 |
| Lighting | 4 |
| ModifierLocal | 4 |
| Popup | 4 |
| WindowInsetsRulers | 4 |
| DrawAnnotation | 4 |
| TextOverflow | 4 |
| AnimatedValue (Animation Core) | 4 |
| Effect | 4 |
| Button | 4 |
| FloatingActionButton | 4 |
| NavigationRail | 4 |
| Slider | 4 |
| Surface | 4 |
| BasicMarquee | 3 |
| Focusable | 3 |
| Image | 3 |
| Scrollable | 3 |
| Scroller | 3 |
| SnapFlingBehavior | 3 |
| Transformable | 3 |
| RelativePaddingFrom | 3 |
| Row | 3 |
| WindowInsetsPadding | 3 |
| Autofill | 3 |
| Dialog | 3 |
| Layout | 3 |
| LookaheadScope | 3 |
| Shadow | 3 |
| TextDecoration | 3 |
| Animatable | 3 |
| Key | 3 |
| Saver | 3 |
| PullRefresh | 3 |
| Theme | 3 |
| AndroidExternalSurface | 2 |
| BringIntoView | 2 |
| Canvas | 2 |
| DrawBackground | 2 |
| InteractionSource | 2 |
| ProgressSemantics | 2 |
| ReceiveContent | 2 |
| Toggleable | 2 |
| ContextualFlowColumn | 2 |
| ContextualFlowRow | 2 |
| Blur | 2 |
| InspectorInfoInComposedModifier | 2 |
| ModifierCompositionLocal | 2 |
| NestedScroll | 2 |
| NestedScrollInterop | 2 |
| Painter | 2 |
| PointerIcon | 2 |
| Scale | 2 |
| Brush | 2 |
| BaselineShift | 2 |
| LineBreak | 2 |
| ParagraphStyle | 2 |
| SpanStyle | 2 |
| TextStyle | 2 |
| Dp | 2 |
| LookaheadAnimationVisualDebug | 2 |
| Transition (Animation) | 2 |
| InfiniteTransition | 2 |
| AlertDialog | 2 |
| AppBar | 2 |
| BottomNavigation | 2 |
| BottomSheetScaffold | 2 |
| Card | 2 |
| Drawer | 2 |
| ExposedDropdownMenu | 2 |
| IconButton | 2 |
| Menu | 2 |
| ProgressIndicator | 2 |
| BackgroundTextMeasurement | 1 |
| BasicTextFieldValue | 1 |
| Clickable | 1 |
| ClickableText | 1 |
| CustomTouchSlop | 1 |
| DarkTheme | 1 |
| Draggable | 1 |
| Draggable2D | 1 |
| HandwritingDetector | 1 |
| Hoverable | 1 |
| Indication | 1 |
| InlineTextContent | 1 |
| Magnifier | 1 |
| Scrollable2D | 1 |
| ScrollableArea | 1 |
| Selectable | 1 |
| TapGesture | 1 |
| TextAutoSize | 1 |
| AspectRatio | 1 |
| Box | 1 |
| BoxWithConstraints | 1 |
| Spacer | 1 |
| VisibleModifier | 1 |
| WindowInsets | 1 |
| WindowInsetsConnection | 1 |
| AlignmentLine | 1 |
| Alpha | 1 |
| InspectableModifier | 1 |
| OnGloballyPositioned | 1 |
| OnPlaced | 1 |
| PlacementScopeCoordinates | 1 |
| PlatformTextInputModifierNode | 1 |
| Rotate | 1 |
| SemanticsProperties | 1 |
| SetFrameRate | 1 |
| SetFrameRateCategory | 1 |
| SoftwareKeyboardController | 1 |
| SoundEffect | 1 |
| TaskDispatchers | 1 |
| ZIndexModifier | 1 |
| MeshGradient | 1 |
| PathEffect | 1 |
| AnnotatedStringFromHtml | 1 |
| LineHeightStyle | 1 |
| TextMotion | 1 |
| AnimatedValue (Animation) | 1 |
| AnimationModifier | 1 |
| Crossfade | 1 |
| EnterExitTransition | 1 |
| AnimationSpec | 1 |
| KeyframesWithSplineBuilder | 1 |
| PathEasing | 1 |
| AnimatedVector | 1 |
| SaveableStateHolder | 1 |
| BackdropScaffold | 1 |
| Badge | 1 |
| ContentAlpha | 1 |
| Elevation | 1 |
| ModalBottomSheet | 1 |
| Swipeable | 1 |
| SwipeToDismiss | 1 |
| Text | 1 |

## What's in this branch

| Path | What it is |
| --- | --- |
| `index.html` | Self-contained gallery — [open via htmlpreview](https://htmlpreview.github.io/?https://github.com/yschimke/compose-ui-samples/blob/design-artifacts/compose-ui-samples/index.html) |
| `compare.html` | SVG↔PNG comparison with a live structural-similarity score — [open via htmlpreview](https://htmlpreview.github.io/?https://github.com/yschimke/compose-ui-samples/blob/design-artifacts/compose-ui-samples/compare.html) |
| `catalog.json` | Machine-readable catalog (`design-parity-catalog/v1`): components, variants, design tokens, greenlines, and per-variant `livePreview` deep links |
| `images/` | Rendered PNGs — the source of truth for each variant |
| `wireframes/` | One editable SVG per component (layout-inspector tree → token-styled shapes) |

## Using it

- **Figma / Stitch / Claude Design** — import `catalog.json` + `images/` as a sticker sheet.
- **Browse** — open `index.html` through htmlpreview (link above), or clone the branch and open it locally.
- **Customise** — open the [live preview server](https://preview.coo.ee/compose-ui-samples/) (or any image's `livePreview` link in `catalog.json`) to re-render a component under different themes / locales / devices.
- **Adopt structure** — the `wireframes/*.svg` are plain vector files; drop one into any editor to start from the real layout instead of tracing a screenshot.

## Provenance

Generated by the [`Design Artifacts`](https://github.com/yschimke/compose-ui-samples/actions/workflows/design-artifacts.yml)
workflow: `compose-preview bundle pack` → catalog-export driver → force-push to
this branch. The render is the source of truth.

> ⚠️ **This branch is regenerated (force-pushed) from `main`** — weekly and after
> catalog/renderer changes. Don't commit work here by hand; it will be
> overwritten on the next run.
