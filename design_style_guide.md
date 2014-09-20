# Clay.io Design Style Guide

## Contents  

### 1. [Branding](#branding)
  1. [Colors](#colors)
  2. [Logos](#logos)
  3. [Badges](#badges)

### 2. [Site Styling](#styling)
  1. [Fonts](#fonts)
  2. [Element styling](#elements)
  3. [Breakpoints](#breaks)

---

## 1. Branding <a name="branding"></a>

### 1.1 Colors <a name="colors"></a>
_Branding colors_  

Name              | Code       | HEX    | RGB           | Color
------------------|------------|--------|---------------|--------
Primary Orange    | $orange    | fcaa2f | 252, 170, 47  | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/branding/colors/primary_orange.png)
Primary Blue      | $blue      | 67afe6 | 103, 175, 230 | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/branding/colors/primary_blue.png)

_Text colors_  

Name              | Code       | HEX    | RGB           | Color
------------------|------------|--------|---------------|--------
Dark gray         | $grayDark  | 262626 | 38, 38, 38    | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/branding/colors/dark_gray.png)
Light gray        | $grayLight | 757575 | 117, 117, 117 | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/branding/colors/light_gray.png)

_Element styling_  

Name              | Code       | HEX    | RGB           | Color
------------------|------------|--------|---------------|--------
Background        | $bgColor   | f2f2f2 | 242, 242, 242 | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/branding/colors/background.png)
White             | $white     | ffffff | 255, 255, 255 | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/branding/colors/white.png)
Near white        | $          | f7f7f7 | 247, 247, 247 | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/branding/colors/near_white.png)
Disabled gray     | $          | cccccc | 204, 204, 204 | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/branding/colors/disabled_gray.png)
Divider           | $divider   | dedede | 222, 222, 222 | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/branding/colors/divider.png)  

### 1.2 Logos <a name="logos"></a>
Logos are primarily in .svg and .png formats.  

_Note: linked images below are reference only._

Name              | Image
------------------|--------------
logo_standard     | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/branding/logos/logo_standard.png)
logo_alt          | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/branding/logos/logo_alt.png)
logo_cloud        | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/branding/logos/logo_cloud.png)  

### 1.3 Badges <a name="badges"></a>
Can be used by on promotional material or to link to games  

_Note: linked images below are reference only._  

Name          | Image
--------------|--------------
gray          | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/branding/badges/gray.png)
gray_alt      | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/branding/badges/gray_alt.png)
gray_mini     | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/branding/badges/gray_mini.png)
orange        | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/branding/badges/orange.png)
orange_alt    | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/branding/badges/orange_alt.png)
orange_mini   | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/branding/badges/orange_mini.png)  

---

## 2. Site Styling <a name="styling"></a>

### 2.1 Fonts <a name="fonts"></a>

#### Branding Font

To be used exclusively on logo and promo image material.
- FF Enzo

#### Site Font

To be used globally across the Clay.io site and apps
- Roboto

###### Font Sizing

Base scaling: 1rem = 10pt  

Size      | Name
----------|--------
1.2rem    | Small
1.6rem    | Medium
2.4rem    | Large
3.6rem    | X-Large
4.2rem    | Huge  

#### Icon Font

Name                  | Unicode   | Icon
----------------------|-----------|--------
icon-star             | 0xe800    | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/site_styling/icon_font/star.png)
icon-star-half-fill   | 0xe801    | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/site_styling/icon_font/star_half.png)
icon-share            | 0xe802    | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/site_styling/icon_font/share.png)
icon-market           | 0xe803    | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/site_styling/icon_font/market.png)
icon-back-arrow       | 0xe804    | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/site_styling/icon_font/back_arrow.png)
icon-close            | 0xe805    | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/site_styling/icon_font/close.png)
icon-chevron-left     | 0xe806    | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/site_styling/icon_font/chevron_left.png)
icon-chevron-right    | 0xe807    | ![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/site_styling/icon_font/chevron_right.png)  

### 2.2 Element Styling <a name="elements"></a>  

![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/site_styling/assets/buttons.png)

###### Buttons
_Rounded button_  
- Corner radii: 20px  
- Height: 40px
- Disabled: 50% opacity
- Standard button shadow

  ```
  box-shadow: 1px 1.732px 10px 0px rgba(0, 0, 0, 0.3);
  ```

  - Primary rounded button:
    - Fill color: Primary orange
    - Text color: White
  - Secondary rounded button:
    - Fill color: White
    - Text color: Primary blue  

![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/site_styling/assets/checkboxes.png)

_Check box_
- Corner radii: 3px
- Width: 20px
- Height: 20px
- Selected color: Primary orange
- Normal color: Disabled gray  

![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/site_styling/assets/radiobuttons.png)

_Radio button_
- Width: 20px
- Height: 20px
- Selected color: Primary orange
- Normal color: Disabled gray  

![Alt text](https://github.com/claydotio/design-assets/blob/master/style_guide_references/site_styling/assets/inputs.png)

###### Input fields

_Text input field_
- Corner radii: 3px
- Background color: White
- Stroke: 1px
  - Normal:
    - Stroke color: #e6e6e6
  - Active:
    - Stroke color: #cccccc
- Hint text color: Disabled gray
- Typed text: Dark gray

###### Modals

- Modal corner radii: 3px  
- Dark overlay: 70% black  
- Modal shadow

  ```
  box-shadow: 0px 0px 20px 0px rgba(0, 0, 0, 0.3);
  ```  

  _Close icon_
  - Close button shadow

  ```
  opacity: 0.75;
  text-shadow: 0px 0px 20px rgba(0, 0, 0, 0.75);
  ```

### 2.3 Breakpoints <a name="breaks"></a>
Standard media-query breakpoints to be used in the site design

- 320px
- 360px
- 480px
- 600px