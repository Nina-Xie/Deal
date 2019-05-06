# Deal
Created by: <i>Yichen Feng (iOS), Nina Xie (iOS), Joyce Huang (Backend), Xiangyi Zhao (Backend)</i>

<strong> A buying and selling app designed for the Cornell community </strong> 

<p>Deal helps Cornell students to sell their used items that are not needed anymore as well as buy used items from others with cheaper prices. </p>

<p>The users first start with signing in with their Google accounts. After loading, they can view all items that are currently on the platform on the "Deal" explore page. Through the search bar, they can search for a specific keyword in items' names or descriptions. 
Clicking into a specific item cell, they can view more information of it, including the item name, price, description and images, on its Detail View. They can scroll the description text vertically to see the full length, and can scroll the image collection view horizontally to see all images (up to 6). 
Tabbing on the seller button, they can go into the seller's profile page and see seller information. 
Back on the item's detail view, through the tool bar on the bottom, one can add the item to "My Favorites" or view and leave comments. </p>

<p>The users can navigate to their own profile page to change the profile picutre and user information. They can also view their favorited and on sale items.</p>

<p>Users can post their own items to the platform through the add feature. Later if an item is sold or the seller wants to delete it, the seller will be able to remove that on its detail page. </p>

<p>Deal does not yet accomplish all of our envisioned features such as sending system notifications to users and message chatting between buyers and sellers. We would love to further work on Deal to actually bring it to our campus in the future.


### Login, User Profile Page (Favorites and OnSale)
### Home Screen: Items Display, Search Bar
### Detail Screen: Item Info, Seller Page/Like/Comment
### Post Screen: Post New Item


### iOS:
NSLayoutConstraint - used to place views as designed, and fit various screen dimensions.

GoogleSignIn API - implemented to get information of the user that is currently signed in.

UITabBarController - displayed at bottom of main ViewControllers with icons for each screen, and ability to navigate between screens. User is brought to their desired page upon click of an icon.

UICollectionView - implemented in DealVC for items and DetailVC for images. 
UITableView - implements in CommentVC for comments.

UIImagePickerController - integrated for the user to upload item images and profile picture.


### Backend:

## Authors:
Yichen Feng
Nina Xie
Joyce Huang
Xiangyi Zhao

©2019 by Fx&Hz
