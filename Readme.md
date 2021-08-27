<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128643529/10.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E1610)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [Window1.xaml](./CS/DockingAndBarsIntegration/Window1.xaml) (VB: [Window1.xaml](./VB/DockingAndBarsIntegration/Window1.xaml))
* [Window1.xaml.cs](./CS/DockingAndBarsIntegration/Window1.xaml.cs) (VB: [Window1.xaml.vb](./VB/DockingAndBarsIntegration/Window1.xaml.vb))
<!-- default file list end -->
# How to: Embed a Bar into a Dock Panel


<p>This example shows how to embed a bar from the DXBars library into a dock panel.</p>
<p>Dock panels embed bar containers at their top edges, allowing bars to be displayed in these containers. To add a bar to a dock panel's bar container, the name of the target bar container is assigned to the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfBarsBar_DockInfotopic">Bar.DockInfo</a>.<a href="https://documentation.devexpress.com/#WPF/DevExpressXpfBarsBarDockInfo_ContainerNametopic">ContainerName</a> property. This name matches the name of the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfDockingBaseLayoutItem_HeaderBarContainerControlNametopic">LayoutPanel.HeaderBarContainerControlName</a> property's value.</p>

<br/>


