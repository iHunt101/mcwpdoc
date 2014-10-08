# Megamenu Dropdown

**MediaCenter** supports Megamenu Dropdown, both vertical and horizontal, with the help of two plugins that comes bundled with the theme namely : **Visual Composer** plugin and **MediaCenter Extensions** plugin.

## Building a megamenu dropdown item

### 1. Static Block Post Type

A megamenu item in **MediaCenter** theme is a **Static Block**. This **Static Block** is available on activating **MediaCenter Extensions** Plugin.

![](https://raw.githubusercontent.com/ibndawood/mcwpdoc/master/assets/images/admin-static-content.png)

### 2. Enable Visual Composer for Static Block

1. Navigate to **Settings > Visual Composer**.
2. In **Content Types** under **General Settings** tab , make sure **static_block** is checked.<br/>![](https://raw.githubusercontent.com/ibndawood/mcwpdoc/master/assets/images/vc-settings.png)
3. Go to **Static Content > Add New** and make sure it has a button just below the title with visual composer icon and text that reads **Backend Editor**.<br/>![](https://raw.githubusercontent.com/ibndawood/mcwpdoc/master/assets/images/visual-composer-button.png)

### 3. Add a new megamenu item

1. Navigate to **Static Content > Add New**.
2. Give it a title, lets say **"Test Megamenu Item"** item. The title is not used anywhere in displaying the menu.
3. Click on **Backend Editor**. It will display Visual Composer Backend Editor. We will use this back end editor to build our megamenu item.<br/>![](https://raw.githubusercontent.com/ibndawood/mcwpdoc/master/assets/images/test-megamenu-item.png)
4. Let us add a simple text block. Click on **Add text block** button and the result will look like this.<br/>![](https://raw.githubusercontent.com/ibndawood/mcwpdoc/master/assets/images/add-text-block.png)
5. Click on **Publish** button.

### 4. Adding megamenu item as a submenu to a menu item

1. Navigate to **Appearance > Menus**.
2. On top right corner of your screen, you will find a dropdown menu **Screen Options**. Click on it.
3. In the dropdown that appears, check on **Static Content Blocks** under **Show on screen**. You will now see **Static Content Blocks** listed in the left side. <br/>![](https://raw.githubusercontent.com/ibndawood/mcwpdoc/master/assets/images/screen-options.png)<br/><br/>![](https://raw.githubusercontent.com/ibndawood/mcwpdoc/master/assets/images/static-content-block-left-menu.png)
4. Choose the menu you want to edit. In my case I've chose a menu that is hooked to **Main Navigation** location.
5. Now check the **Test Megamenu item** and click on **Add to menu**.
6. Drag the **Test Megamenu item** box and drop it under any existing menu as a submenu.<br/>
![](https://raw.githubusercontent.com/ibndawood/mcwpdoc/master/assets/images/static-block-submenu.png)
7. Click on **Save Menu**.
8. Now the megamenu will is added as a submenu and it should look like this: <br/> ![](https://raw.githubusercontent.com/ibndawood/mcwpdoc/master/assets/images/submenu.megamenu-as-submenu.png)

<div class="alert alert-danger">**Alert :** Please do not use **Static Content Block** as a top level menu item or as submenu menu item beyond level 1. Do not use other menu items with **Static Content Block** menu item.</div>
