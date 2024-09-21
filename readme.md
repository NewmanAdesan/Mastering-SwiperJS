JULY 2024

basically swiperJs is divide into 2 concept elements and their configuration(styles, function, e.t.c)
basically it has 6 components 
- the parent container, 
- the slides wrapper
- the slides
- the pagination
- the navigation
- the scrollbar

we can interact the parent container(swiper UI), the pagination, the navigation, the scrollbar in 4 ways
- via parameter
- via properties
- via methods
- via events
- via css variables/css classes
    
----------------------------





SEPTEMBER 2024 

4 Basic ways to configure our SWIPER's Functionality/Behaviour
* PARAMETERS
* METHODS & PROPERTIES
* EVENTS
* MODULES

<br />

PARAMETERS
* a11y (accessibility)
* allowSlideNext/allowSlidePrev/allowTouchMove
* autoHeight
* autoplay/cardEffect/creativeEffect/controller/coverflowEffect/cubeEffect/cssMode/fadeEffect/flipEffect/freeMode/grid/hashNavigation/history (special-effect-based---modules)
* breakpoint/breakpointBase
* centerInsufficientSlides/centeredSlides/centeredSlidesBounds
* containerModifierClass
* createElement
* direction
* effect (slide-transition-pattern)
* enabled (no-event-no-interaction)
* focusableElements
* followFinger (**interesting)
* grabCursor (improves-desktop-ux)
* height (**technically-interesting)
* init (control-swiper-instance-initialization)
* initialSlide
* injectStyles/injectStylesUrls

<br />

MODIFER CSS CLASSES: A BASIC UNDERSTANDING <br >
one of the basic understanding of SWIPERJS is that when you set a configuration for the swiper via a parameter like autoHeight: true, the swiper engine will automtically add the class "swiper-autoheight" to the swiper html element. this means the is a one-to-one mapping of parameter-configurations to a css-class. this css-classes are called MODIFIER CSS CLASSES because they modify the behaviour or appearance of the swiper instance. even you can use this modifier classes to add special styling based on current-state/configuration of the swiper. by default this classes are prefixed by "swiper-" e.g "swiper-horizontal", "swiper-autoheight" BUT you can change this prefix via the `containerModifierClass parameter`

<br />

THE CREATE-ELEMENTS PARAMETER: SETUP SWIPER LIKE A PRO <br>
with this html below and the createElements property set to true, you can easily setup
```html
<!-- YOUR CODE -->
<div class="swiper">
    <div>Slide 1</div>
    <div>Slide 2</div>
    <div>Slide 3</div>
</div>
```

```html
<!-- THE RESULT -->
<div class="swiper">
    <div class="swiper-wrapper">
        <div class="swiper-slide">Slide 1</div>
        <div class="swiper-slide">Slide 2</div>
        <div class="swiper-slide">Slide 3</div>
    </div>
    <div class="swiper-pagination"></div>
    <div class="swiper-button-next"></div>
    <div class="swiper-button-prev"></div>
</div>
```

<br />

FOCUSABLE-ELEMENT PARAMETER: iMPORTANT FOR INTERACTIVE FORM ELMENTS OR MEDIA CONTROLS INSIDE THE SWIDER <br>
such that we can set some html elements in our swiper element to disable the slide changes when they are focused on. check the docs for the default-value of this parameter





    
