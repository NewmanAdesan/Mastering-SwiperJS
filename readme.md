---------  JULY 2024  ------------------------------------------------------------
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
    - via css variables/ css classes


--------------------------------------------------------------------------------





---------  SEPTEMBER 2024  ------------------------------------------------------------
4 Basic ways to configure our SWIPER's Functionality/Behaviour
* PARAMETERS
* METHODS & PROPERTIES
* EVENTS
* MODULES


PARAMETERS
    * a11y (accessibility)
    * allowSlideNext/allowSlidePrev/allowTouchMove
    * autoHeight
    * autoplay/cardEffect (module-based)
    * breakpoint/breakpointBase
    * centerInsufficientSlides/centeredSlides/centeredSlidesBounds


one of the basic understanding of SWIPERJS is that when you set a configuration for the swiper via a parameter like autoHeight: true, the swiper engine will automtically add the class "swiper-autoheight" to the swiper html element. this means the is a one-to-one mapping of parameter-configurations to a css-class. this css-classes are called MODIFIER CSS CLASSES because they modify the behaviour or appearance of the swiper instance. even you can use this modifier classes to add special styling based on current-state/configuration of the swiper. by default this classes are prefixed by "swiper-" e.g "swiper-horizontal", "swiper-autoheight" BUT you can change this prefix via the `containerModifierClass parameter`


    
