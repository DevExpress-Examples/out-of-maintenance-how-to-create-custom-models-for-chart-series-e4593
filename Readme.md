# How to create custom models for chart series 


<p>This example illustrates how to create bar custom models.</p>
<p>To do this, create an object that represents a custom model of a particular series (<a href="http://documentation.devexpress.com/#WPF/clsDevExpressXpfChartsCustomBar2DModeltopic"><u>CustomBar2DModel</u></a>) and assign it to the <strong>Model </strong>property of a corresponding series type (<a href="http://documentation.devexpress.com/#WPF/DevExpressXpfChartsBarSeries2D_Modeltopic"><u>BarSeries2D.Model</u></a>).</p>
<p>Then, create the System.Windows.Controls.ControlTemplate object which contains all necessary visual elements to create your own custom model. Assign this template to the <strong>Point</strong><strong>Template</strong> property of a series custom model (<a href="http://documentation.devexpress.com/#WPF/DevExpressXpfChartsCustomBar2DModel_PointTemplatetopic"><u>CustomBar2DModel.PointTemplate</u></a>).</p>
<p> <br /><b>See Also:</b> <br /><a href="https://www.devexpress.com/Support/Center/p/T209781">How to customize the appearance of selected series points</a> </p>

<br/>


