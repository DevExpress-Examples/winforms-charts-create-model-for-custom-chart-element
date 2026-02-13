<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/228585792/24.2.1%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T848258)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->

# Chart for WinForms - Create a Model for a Custom Chart Element

This example creates and registers a model (`CustomPointColorizerModel`) for a custom chart element (`CustomPointColorizer`).

![Custom Colorizer - WinForms Chart Designer, DevExpress](images/custom-colorizer-in-designer.png)

When a user modifies chart element properties in the Chart Designer, the changes are applied to the corresponding *chart element model*. Model changes take effect on the actual chart element after the user clicks **OK**. The Chart Control includes predefined models for built-in elements. If you create a custom element (for example, a colorizer), you must also create and register a model for this element to allow users to edit its options in the Chart Designer.

## Files to Review

* [Form1.cs](./CS/CustomChartElementModel/Form1.cs) (VB: [Form1.vb](./VB/CustomChartElementModel/Form1.vb))
* [CustomColorizerEditor.cs](./CS/CustomChartElementModel/CustomColorizerEditor.cs) (VB: [CustomColorizerEditor.vb](./VB/CustomChartElementModel/CustomColorizerEditor.vb))
<!-- default file list end -->

## Documentation

- [Chart Designer for End Users](https://docs.devexpress.com/WindowsForms/114127/controls-and-libraries/chart-control/end-user-features/chart-designer-for-end-users)
- [ChartDesigner.RegisterCustomModelType(Type, Type) Method](https://docs.devexpress.com/WindowsForms/DevExpress.XtraCharts.Designer.ChartDesigner.RegisterCustomModelType(System.Type-System.Type))
- [ChartColorizerBaseModel](https://docs.devexpress.com/WindowsForms/DevExpress.XtraCharts.Designer.ChartColorizerBaseModel?p=netframework)

<!-- feedback -->
## Does This Example Address Your Development Requirements/Objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=winforms-charts-create-model-for-custom-chart-element&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=winforms-charts-create-model-for-custom-chart-element&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
