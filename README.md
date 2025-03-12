# awesome-exb
List of ESRI Experience Builder community widgets

| Widget | Link | Description | 
| -------- | ------- | ------- |
| Layer Focus Button | <a target="_blank" href="https://community.esri.com/t5/experience-builder-custom-widgets/layer-focus-button-custom-experience-builder/m-p/1592375/highlight/true#M479">ArcGIS Community</a> | In the settings panel you can choose a map and a layer, and then the UI of the widget is a single button that when clicked will turn that selected layer on and all other layers off. It is not extensively tested, so use at your own risk and please post if you make any improvements to it. |
| Draw | [ArcGIS Community](https://community.esri.com/t5/experience-builder-custom-widgets/draw-widget-eb-1-7-0-1-28-22/ta-p/1138481)| * The widget allows you to draw in a 2D map view.<br>* You can edit graphics that you have drawn (symbology and geometry).<br>* You can draw points, lines, polygons, text |
| Re-designed Draw | [ArcGIS Community](https://community.esri.com/t5/experience-builder-custom-widgets/re-designed-draw-widget/m-p/1352200/highlight/true#M137) | Re-designed version the draw widget by @RobertScheitlin__GISP. His draw widget has a number of advantages over the OOTB draw widget including the ability to use text, editing a drawing and more drawing tools. However, the user interface needs some improvement.<br><br>This widget has modified his code to improve the overall user experience.<br><br>Changes:<br>* Many of the internal menus were displaying behind other menus making them difficult or impossible to access. These issues should all be fixed.<br>* Text added to clarify if the widget is in draw or edit mode and how to access the other mode.<br>* The draw tools have been placed in a flexbox div to make the layout better organized.<br>* The options button has been widened and labeled to make it clear that is different than the draw tool buttons.<br>* The Undo/Redo buttons will only display if it is possible to undo or redo something.<br>* Text in the delete button will clarify if deleting a single or all graphics.<br>* Text options menu has been re-ordered and re-designed with additional text to clarify options.<br>* Entering text does not require deleting default text.<br>* Preview will accurately reflect the map symbol regardless of theme font. |
