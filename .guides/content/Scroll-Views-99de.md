If you add lots of views to your layouts, you may have problems on devices with smaller screens—most layouts don’t come with scrollbars to allow you to scroll down the page. 
As an example, when we added seven large buttons to a linear layout, we couldn’t see all of them:

![](.guides/img/80scrollView.png)

To add a vertical scrollbar to your layout, you surround your existing layout with a **< ScrollView>** element like this:

![](.guides/img/81.png)
![](.guides/img/82.png)

To add a horizontal scrollbar to your layout, wrap your existing layout inside a **< HorizontalScrollView>** element instead.
