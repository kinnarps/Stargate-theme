# Stargate-theme

* [Colors](#colors)
* [Links](#links)
* [Buttons](#buttons)
* [Forms](#forms)
* [Background overlay](#background-overlay)


### Colors
- ![#00a8df](https://via.placeholder.com/15/00a8df/00a8df) `#00a8df Kingfisher blue`
- ![#98d6ea](https://via.placeholder.com/15/98d6ea/98d6ea) `#98d6ea Aqua marine`
- ![#f5eb61](https://via.placeholder.com/15/f5eb61/f5eb61) `#f5eb61 Lemon yellow`
- ![#d6fcd5](https://via.placeholder.com/15/d6fcd5/d6fcd5) `#d6fcd5 Polar green`
- ![#91d6ac](https://via.placeholder.com/15/91d6ac/91d6ac) `#91d6ac Spring green`
- ![#e5b9a7](https://via.placeholder.com/15/e5b9a7/e5b9a7) `#e5b9a7 Salmon`
- ![#d22730](https://via.placeholder.com/15/d22730/d22730) `#d22730 Chili red`
- ![#fcafc0](https://via.placeholder.com/15/fcafc0/fcafc0) `#fcafc0 Flamingo pink`
- ![#6d4f47](https://via.placeholder.com/15/6d4f47/6d4f47) `#6d4f47 Cinnamon`
- ![#d0d3d4](https://via.placeholder.com/15/d0d3d4/d0d3d4) `#d0d3d4 Misty grey`
- ![#888C8C](https://via.placeholder.com/15/888C8C/888C8C) `#888C8C Graphite grey`
- ![#eef1f3](https://via.placeholder.com/15/eef1f3/eef1f3) `#eef1f3 Light grey`
- ![#25282a](https://via.placeholder.com/15/25282a/25282a) `#25282a Kin black`

```
$body-bg:                   $white;
$text-color:                $black;
$link-color:                $black;
$link-hover-color:          $graphite-grey;
$link-hover-decoration:     none;

$link-color-light:          $white;
$link-hover-color-light:    $black;
```

### Links

##### Link modifiers
```
a.kingfisher{
  color : $kingfisher-blue;
  text-decoration:none;
    &:hover,&:focus {
      color:$kin-black;
      text-decoration:$link-hover-decoration;
     }
 }
```

```
a.light{
  color : $link-color-light;
  text-decoration:none;
    &:hover,&:focus {
      color:$link-hover-color-light;
      text-decoration:$link-hover-decoration;
     }
 }
```

### Buttons
`.btn .btn-default`<br />
![Button default](https://github.com/kinnarps/Stargate-theme/blob/master/resources/button_default.PNG)

`.btn .btn-primary`<br />
![Button primary](https://github.com/kinnarps/Stargate-theme/blob/master/resources/button_primary.PNG)

`.btn .btn-blue`<br />
![Button blue](https://github.com/kinnarps/Stargate-theme/blob/master/resources/button_blue.PNG)

`.btn .btn-pink`<br />
![Button pink](https://github.com/kinnarps/Stargate-theme/blob/master/resources/button_pink.PNG)

`.btn .btn-yellow`<br />
![Button yellow](https://github.com/kinnarps/Stargate-theme/blob/master/resources/button_yellow.PNG)

`.btn .btn-mistygrey`<br />
![Button primary](https://github.com/kinnarps/Stargate-theme/blob/master/resources/button_mistygrey.PNG)

##### Button modifiers
`.btn .btn-primary .small`<br />
![Button primary small](https://github.com/kinnarps/Stargate-theme/blob/master/resources/button_primary_small.PNG)

### Forms

##### Form modifiers
`input.narrow` : Less padding on input<br />
`label.proper` : Removes text transform uppercase<br />
`label.block`  : Display block<br /><br />

### Background overlay
```
$('.background-overlay').toggleClass("show");
```
