# How to: Embed a Bar into a Dock Panel

This example embeds a bar from the **Bars** library into a dock panel.

Dock panels embed bar containers at their top edges, allowing bars to be displayed in these containers. To add a bar to a dock panel's bar container, the name of the target bar container is assigned to the [BarDockInfo.ContainerName](https://docs.devexpress.com/WPF/DevExpress.Xpf.Bars.BarDockInfo.ContainerName) property. This name matches the name of the [LayoutPanel.HeaderBarContainerControlName](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.BaseLayoutItem.HeaderBarContainerControlName) property's value.

![image](https://user-images.githubusercontent.com/12169834/173895946-4bd26dde-8dfc-4e9c-83dd-2d4d42455a0c.png)

<!-- default file list -->
## Files to look at:

* [Window1.xaml](./CS/DockingAndBarsIntegration/Window1.xaml) (VB: [Window1.xaml](./VB/DockingAndBarsIntegration/Window1.xaml))
<!-- default file list end -->

## Documentation

- [Dock UI Items](https://docs.devexpress.com/WPF/7209/controls-and-libraries/layout-management/dock-windows/dock-items)
- [LayoutGroup](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.LayoutGroup)
- [Bar.DockInfo](https://docs.devexpress.com/WPF/DevExpress.Xpf.Bars.Bar.DockInfo)
- [LayoutPanel.HeaderBarContainerControlName](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.BaseLayoutItem.HeaderBarContainerControlName)

## More Examples

- [WPF Dock Layout Manager - Create a Simple Layout of Dock Panes](https://github.com/DevExpress-Examples/how-to-create-a-simple-layout-of-dock-panes-e1600)
- [WPF Dock Layout Manager - Create a Complex Layout of Dock Panels](https://github.com/DevExpress-Examples/how-to-create-a-complex-layout-of-dock-panels-e1663)
- [WPF Dock Layout Manager - Сreate a DocumentGroup with Two Tabs](https://github.com/DevExpress-Examples/how-to-create-a-documentgroup-with-two-tabs-e1670)
- [WPF Dock Layout Manager - Create Tabbed and Document Groups](https://github.com/DevExpress-Examples/how-to-create-a-tabbedgroup-and-documentgroup-groups-e1656)
