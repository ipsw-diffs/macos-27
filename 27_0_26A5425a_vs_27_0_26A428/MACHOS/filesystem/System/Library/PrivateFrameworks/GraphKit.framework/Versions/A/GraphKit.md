## GraphKit

> `/System/Library/PrivateFrameworks/GraphKit.framework/Versions/A/GraphKit`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__DATA.__data`

```diff

 31.0.0.0.0
-  __TEXT.__text: 0x28810
+  __TEXT.__text: 0x27f8c
   __TEXT.__objc_methlist: 0x16dc
   __TEXT.__const: 0x3f8
   __TEXT.__cstring: 0x357d
-  __TEXT.__unwind_info: 0x5d0
+  __TEXT.__unwind_info: 0x728
   __TEXT.__objc_stubs: 0x33e0
   __TEXT.__auth_stubs: 0x4f0
   __TEXT.__objc_classname: 0xc6
Functions:
~ +[GRChartView defaultPropertyForKey:] : 56 -> 44
~ +[GRChartView setDefaultProperty:forKey:] : 260 -> 236
~ +[GRChartView setDefaultProperties:] : 128 -> 116
~ -[GRChartView awakeFromNib] : 260 -> 248
~ -[GRChartView setDefaultPlotColors:] : 80 -> 68
~ -[GRChartView valueClassForBinding:] : 500 -> 488
~ -[GRChartView propertyForKey:] : 168 -> 156
~ -[GRChartView didSetProperty:forKey:replacingOldValue:andShouldReload:andRelayout:andRedisplay:] : 752 -> 728
~ -[GRChartView dataSet:propertyChangedForKey:from:to:] : 292 -> 280
~ -[GRChartView properties] : 56 -> 44
~ -[GRChartView reloadData] : 96 -> 84
~ -[GRChartView reloadDataInRange:] : 152 -> 140
~ -[GRChartView setNeedsToReloadData:inRange:] : 328 -> 316
~ -[GRChartView canvasRect] : 228 -> 216
~ -[GRChartView plotRect] : 208 -> 196
~ -[GRChartView _updateCopyOnScrollSetting] : 148 -> 136
~ -[GRChartView delayedRedraw:] : 148 -> 136
~ -[GRChartView drawRect:] : 2668 -> 2644
~ -[GRChartView isOpaque] : 156 -> 144
~ -[GRChartView _crossDataSetDependenciesExist] : 140 -> 128
~ -[GRChartView addDataSet:loadData:] : 228 -> 216
~ -[GRChartView moveDataSetAtIndex:toIndex:] : 316 -> 304
~ -[GRChartView removeAllDataSets] : 92 -> 80
~ -[GRChartView removeDataSet:] : 180 -> 156
~ -[GRChartView removeDataSetAtIndex:] : 188 -> 176
~ -[GRChartView _justifyFromSelection:] : 568 -> 532
~ -[GRChartView _applyZoomHistoryAtIndex:] : 272 -> 260
~ -[GRChartView _clipViewBoundsChanged:] : 252 -> 228
~ -[GRChartView _rememberCurrentPositionAndZoomClearingSuccessiveEntries:] : 408 -> 384
~ -[GRChartView _restorePreviousPositionAndZoom] : 200 -> 176
~ -[GRChartView _restoreNextPositionAndZoom] : 160 -> 136
~ -[GRChartView _setZoomX:Y:] : 740 -> 716
~ -[GRChartView _zoomToPercent:] : 1152 -> 1128
~ -[GRChartView horizontalZoomTo:] : 64 -> 52
~ -[GRChartView verticalZoomTo:] : 68 -> 56
~ -[GRChartView zoomTo:] : 64 -> 52
~ -[GRChartView _log2HorizontalZoomTo:] : 68 -> 56
~ -[GRChartView _log2VerticalZoomTo:] : 72 -> 60
~ -[GRChartView _log2ZoomTo:] : 68 -> 56
~ -[GRChartView zoomToRect:] : 1144 -> 1132
~ -[GRChartView _updateScrollers] : 1140 -> 1128
~ -[GRChartView createSelectionRectangle] : 280 -> 268
~ -[GRChartView sizeSelectionRectangle] : 592 -> 580
~ -[GRChartView moveLeft:] : 128 -> 104
~ -[GRChartView moveLeftAndModifySelection:] : 172 -> 148
~ -[GRChartView moveRight:] : 128 -> 104
~ -[GRChartView moveRightAndModifySelection:] : 172 -> 148
~ -[GRChartView mouseDown:] : 468 -> 456
~ -[GRChartView mouseDragged:] : 592 -> 580
~ +[GRAxes defaultPropertyForKey:] : 60 -> 48
~ +[GRAxes setDefaultProperty:forKey:] : 260 -> 236
~ +[GRAxes setDefaultProperties:] : 128 -> 116
~ -[GRAxes encodeWithCoder:] : 292 -> 268
~ -[GRAxes propertyForKey:] : 80 -> 68
~ -[GRAxes didSetProperty:forKey:replacingOldValue:andShouldReload:andRelayout:andRedisplay:] : 1276 -> 1264
~ -[GRAxes properties] : 44 -> 32
~ -[GRAxes setCanvasRect:] : 264 -> 252
~ -[GRAxes legendRect] : 2964 -> 2976
~ -[GRAxes setNeedsLayout:] : 56 -> 44
~ -[GRAxes drawLegendRect:] : 1460 -> 1448
~ -[GRAxes drawBackgroundInRect:] : 476 -> 440
~ -[GRAxes drawGridRect:] : 72 -> 60
~ -[GRAxes drawAxesRect:] : 512 -> 500
~ +[GRPieAxes initialize] : 444 -> 432
~ -[GRPieAxes legendLabels] : 384 -> 372
~ -[GRPieAxes drawLegendSampleInRect:forDataSet:withHighlight:] : 224 -> 212
~ +[GRAreaDataSet initialize] : 252 -> 240
~ -[GRAreaDataSet drawLegendSampleInRect:] : 360 -> 348
~ -[GRAreaDataSet drawDataSetRect:] : 6112 -> 6100
~ -[GRAreaDataSet view:stringForToolTip:point:userData:] : 660 -> 628
~ +[GRColumnDataSet initialize] : 504 -> 492
~ -[GRColumnDataSet drawLegendSampleInRect:] : 360 -> 348
~ -[GRColumnDataSet drawDataSetRect:] : 7480 -> 7652
~ -[GRColumnDataSet view:stringForToolTip:point:userData:] : 612 -> 580
~ +[GRDataSet defaultPropertyForKey:] : 60 -> 48
~ +[GRDataSet setDefaultProperty:forKey:] : 260 -> 236
~ +[GRDataSet setDefaultProperties:] : 128 -> 116
~ +[GRDataSet defaultColors] : 172 -> 160
~ +[GRDataSet setDefaultColors:] : 132 -> 120
~ -[GRDataSet _setOwnerChart:] : 164 -> 152
~ -[GRDataSet encodeWithCoder:] : 396 -> 372
~ -[GRDataSet _setLiteralProperty:forKey:] : 180 -> 156
~ -[GRDataSet propertyForKey:] : 80 -> 68
~ -[GRDataSet didSetProperty:forKey:replacingOldValue:andShouldReload:andRelayout:andRedisplay:] : 368 -> 356
~ -[GRDataSet properties] : 44 -> 32
~ -[GRDataSet _defaultLabelAttributes] : 472 -> 460
~ -[GRDataSet reloadData] : 88 -> 76
~ -[GRDataSet setDataSource:] : 116 -> 104
~ -[GRDataSet setAxes:] : 76 -> 64
~ -[GRDataSet _activeAxes] : 104 -> 92
~ -[GRDataSet selectPrevious] : 96 -> 84
~ -[GRDataSet selectPreviousByExtendingSelection] : 144 -> 132
~ -[GRDataSet selectNext] : 140 -> 128
~ -[GRDataSet selectNextByExtendingSelection] : 124 -> 112
~ -[GRDataSet _supportsCopyOnScroll] : 40 -> 28
~ -[GRDataSet autoPlotColor] : 104 -> 92
~ -[GRDataSet drawLegendSampleInRect:] : 460 -> 436
~ +[GRPieDataSet initialize] : 324 -> 312
~ -[GRPieDataSet setDataSource:] : 836 -> 716
~ -[GRPieDataSet reloadDataInRange:] : 1356 -> 1316
~ -[GRPieDataSet drawLegendSampleInRect:forWedgeIndex:] : 388 -> 356
~ -[GRPieDataSet drawDataSetRect:] : 1540 -> 1520
~ -[GRPieDataSet view:stringForToolTip:point:userData:] : 544 -> 512
~ +[GRLineDataSet defaultMarkers] : 48 -> 36
~ +[GRLineDataSet setDefaultMarkers:] : 72 -> 60
~ -[GRLineDataSet drawLegendSampleInRect:] : 660 -> 648
~ -[GRLineDataSet view:stringForToolTip:point:userData:] : 660 -> 628
~ -[GRSelectionView drawRect:] : 184 -> 172
~ +[GRXYDataSet initialize] : 376 -> 364
~ -[GRXYDataSet setDataSource:] : 1144 -> 984
~ -[GRXYDataSet reloadDataInRange:] : 4360 -> 4168
~ +[GRXYAxes initialize] : 2228 -> 2216
~ -[GRXYAxes computeUnitsForAxis:] : 12784 -> 12772
~ -[GRXYAxes drawLegendSampleInRect:forDataSet:withHighlight:] : 244 -> 232
~ -[GRXYAxes drawGridRect:forAxis:] : 3128 -> 3116
~ -[GRXYAxes drawAxisRect:forAxis:] : 9720 -> 9708
~ -[GRXYAxes valueAtPoint:forAxis:] : 508 -> 496
~ -[GRSliderScroller _layoutScroller] : 700 -> 688
~ -[GRSliderScroller sliderCell] : 80 -> 68
~ -[GRSliderScroller setTitle:] : 96 -> 84
~ _linearInterpolate : 108 -> 104
~ -[GRGradientColor encodeWithCoder:] : 164 -> 140
~ -[GRGradientColor addColor:] : 88 -> 76
~ -[GRGradientColor fillBezierPath:] : 68 -> 56
~ -[GRGradientColor fillBezierPath:withBounds:] : 580 -> 568
~ -[GRGradientColor fillRect:] : 116 -> 104
~ -[GRGradientColor set] : 60 -> 48
```
