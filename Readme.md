<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/IExternalAppointmentCompareSample/Form1.cs) (VB: [Form1.vb](./VB/IExternalAppointmentCompareSample/Form1.vb))
* [MyAppointmentComparer.cs](./CS/IExternalAppointmentCompareSample/MyAppointmentComparer.cs) (VB: [MyAppointmentComparer.vb](./VB/IExternalAppointmentCompareSample/MyAppointmentComparer.vb))
<!-- default file list end -->
# How to sort Appointments with the same time interval


<p>This example illustrates how to sort Appointments with the same time interval. This can be useful if you wish to sort all-day appointments (or daily appointments with the same Start and End values) by your custom rule.</p><p>This functionality may be introduced by implementing a custom <strong>DevExpress.XtraScheduler.Services.Internal.IExternalAppointmentCompareService</strong> service.</p>

<br/>


