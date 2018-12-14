# String Rendering

We've talked about many different string topics in this issue, from Unicode over localization to parsing. But in most cases, strings ultimately have to be drawn on to the screen for the user to see and interact with them. This article covers the basics, best paractices, and common pitfalls of how to present strings in the user interface.

## How to Get Strings onto the Screen

For the sake of simplicity, we'ar first going to focus on what UIKit has to offer in terms of string drawing. Afterward, we'll talk about similarities and differences between iOS and OSX

UIkit comes with multiple classes that can be used to display and edit text on screen. Each is made for specific use cases, and it's important to choose the right tool for the task at hand in order to avoid unnecessary trouble.

## UILabel

UILabel is the simplest way to bring text onto the screen. It's a UIView subclass and is made to display samll a amounts of read-only text. The text can be laid out in a single line or in multiple lines, and it can be clipped in different ways if it doesn't fit into the specified space. Although labels are pretty straightforward to use, thy have a couple of tricks up their sleeves that are worth mentioning.


## 字符串渲染

在西藏中我们已经讨论了很多关于字符串不同的话题，从编码到本地化再到语法分析。但多数情况下，字符串最终还是需要被绘制到屏幕上供用户查看、交互。这篇文章涵盖了最基本、最好的练习，以及在用户界面上呈现字符串可能遇到的常见陷阱。

## 如何将字符串绘制到屏幕上

简单起见我们先看看 UIKit 在字符串渲染方面为我们提供了那些控件。之后我们将讨论一下对于字符串的渲染，iOS 和 OS X 系统中有哪些相似和不同

UIKit 提供了很多可以在屏幕上显示和编辑文本的类。每一个类都是为特定使用情况准备的，的以为了避免不必要的问题，为你手上的任务挑选正确的工具是非常重要的。

## UILabel

**UILable** 是将文本绘制到屏幕上最简单的方式。它是**UIView**的一个子类，用来显示少量的**只读**文本。文本可以被展示在一行或者多行，如果文本不能适应指定的空间我们还可以使用不同的方式裁剪。尽管 label 使用的方式很简单，但是这里有几个技巧还是值得提一提的。

label 默认只显示一行，但是你可以将 **numberOfLines** 属性设为其他值来改变这一行为。将它设置为一个大于**1**的值，文本的行数将会被限制为这个指定的值；如果设置为**0**，则是告诉 label 不管文本占多少行都显示出来。




































