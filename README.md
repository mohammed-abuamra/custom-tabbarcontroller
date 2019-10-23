# custom-tabbarcontroller


How to set top left and right corner radius with desired drop shadow in UITabBar ?


*   Add a coustmeTabBarView
*   Add the cornerRadius to coustmeTabBarView
*   Add the shadow to coustmeTabBarView
*   In  viewDidLayoutSubviews  make the coustmeTabBarView frame equal to tabBar frame.
*   In viewDidAppear Adjust the safe area to the height of the bottom views.
*   In viewDidAppear  Adjust the safe area insets of the embedded child view controller .
*   Add  private func with name addcoustmeTabBarView . 
*   In addcoustmeTabBarView make the coustmeTabBarView frame equal to tabBar frame.
*   In addcoustmeTabBarView addSubview coustmeTabBarView to view
*   In addcoustmeTabBarView  bringSubviewToFront  tabBar to view

*   Add func hideTabBarBorder (optional)
*   In  hideTabBarBorder  make the tabBar background Image &  tabBar shadowImage  to empty image 
*   In  hideTabBarBorder make tabBar clipsToBounds = true
 




