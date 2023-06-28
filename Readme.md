<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/200242632/22.1.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T803618)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# Blazor Form Layout - Change the visibility of DxFormLayout's items and groups

The following example shows how to implement a form that dynamically displays additional inputs based on user choice.

![Final Layout](/result.png)

A user chooses one of the options in Radio Group. Based on selected value, the [Visible](https://docs.devexpress.com/Blazor/DevExpress.Blazor.Base.FormLayoutItemBase.Visible) property of the `DxFormLayoutGroup` and `DxFormLayoutItem` UI elements changes and displays or hides additional inputs. 

## Files to Review

[Index.razor](./CS/DxFormLayoutSelectionDependentInputs/Pages/Index.razor)

## Documentation

* [DxRadioGroup](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxRadioGroup-2.ValueChanged)
* [DxFormLayout](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayout)

## More Examples

[Form Layout - Collapsible Groups](https://github.com/DevExpress-Examples/blazor-form-layout-collapsible-groups)
