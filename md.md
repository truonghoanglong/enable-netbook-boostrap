*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
body{
    font-family: sans-serif;
}

/* Reponsive */
/* Mobile: width < 740px */
@media only screen and (max-width: 46.1875em) {
    
}

/* Tablet: width >= 740px and width < 1024px */
@media only screen and (min-width: 46.25em) and (max-width: 63.9375em) {
    
}

// const $ = document.querySelector.bind(document)
// const $$ = document.querySelectorAll.bind(document)

// document.addEventListener('DOMContentLoaded',()=>{
    
// })
$('.slider').slick({
    infinite: true,
    slidesToShow: 3,
    slidesToScroll: 3,
    dots:true
});