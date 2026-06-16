# Getting Started with the .NET MAUI DateTimePicker
This section explains how to add the Date Time Picker control. It covers only the basic features needed to get started with Syncfusion<sup>&reg;</sup> Date Time Picker.

## Register Syncfusion handler

Make sure to add the namespace.

{% highlight MauiProgram.cs %}
using Syncfusion.Maui.Core.Hosting;
{% endhighlight %} 

Register the Syncfusion core handler in your `CreateMauiApp` method of `MauiProgram.cs` file to use Syncfusion controls.

{% highlight MauiProgram.cs %}
builder.ConfigureSyncfusionCore();
{% endhighlight %}

## Import the DateTimepicker namespace

Add the following namespace in your XAML or C#.

{% tabs %}
{% highlight xaml tabtitle="xaml" %}
xmlns:picker="clr-namespace:Syncfusion.Maui.Picker;assembly=Syncfusion.Maui.Picker"
{% endhighlight %}
{% highlight c# tabtitle="C#" %}
using Syncfusion.Maui.Picker;
{% endhighlight %}
{% endtabs %}

## Add the DateTimepicker component

Create an instance of DateTimepicker and add it to your page.

{% tabs %}
{% highlight xaml tabtitle="XAML" %}
    <picker:SfDateTimePicker />
{% endhighlight %}
{% highlight c# tabtitle="C#" %}
    SfDateTimePicker picker = new SfDateTimePicker();
    this.Content = picker;
{% endhighlight %}
{% endtabs %}

The following gif image illustrates the result of the above code.

![Set Height and Width in .NET MAUI Date Time picker.](maui-date-time-picker-set-height-and-width.png)

N> You can refer to our [.NET MAUI Date Time Picker](https://www.syncfusion.com/maui-controls/maui-datetimepicker) feature tour page for its groundbreaking feature representations. You can also explore our [.NET MAUI Date Time Picker Example](https://github.com/syncfusion/maui-demos/tree/master/MAUI/Picker/SampleBrowser.Maui.Picker/Samples/DateTimePicker/GettingStarted) that shows you how to render the Date Time Picker in .NET MAUI.