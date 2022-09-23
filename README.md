# goit-markup-hw-07
GoIT group Blended-9 SkyArt Домашнє завдання 08 - Адаптивна верстка

Приклад завантаження картинки під всі пристрої

<picture>
   <source
     srcset="./images/team-img/webp/photo-01-desktop.webp 1x, ./images/team-img/webp/photo-01-desktop@2x.webp 2x"
     media="(min-width: 1200px)"
     type="image/webp"
    />
    <source
     srcset="./images/team-img/photo-01-desktop.jpg 1x, ./images/team-img/photo-01-desktop@2x.jpg 2x"
     media="(min-width: 1200px)"
    />
    <source
     srcset="./images/team-img/webp/photo-01-tablet.webp 1x, ./images/team-img/webp/photo-01-tablet@2x.webp 2x"
     media="(min-width: 768px)"
     type="image/webp"
    />
    <source
     srcset="./images/team-img/photo-01-tablet.jpg 1x, ./images/team-img/photo-01-tablet@2x.jpg 2x"
     media="(min-width: 768px)"
    />
    <source
     srcset="./images/team-img/webp/photo-01-mobile.webp 1x, ./images/team-img/webp/photo-01-mobile@2x.webp 2x"
     media="(max-width: 767px)"
     type="image/webp"
    />
    <source
     srcset="./images/team-img/photo-01-mobile.jpg 1x, ./images/team-img/photo-01-mobile@2x.jpg 2x"
     media="(max-width: 767px)"
    />
    <img src="./images/team-img/photo-01-mobile.jpg" alt="Product Designer portrait"
    />
</picture>

 Приклад завантаження картинки тільки під дескпоп

<picture>
    <source
      srcset="./images/what-img/webp/img-01.webp 1x, ./images/what-img/webp/img-01@2x.webp 2x"
      type="image/webp"
    />
    <img 
      srcset="./images/what-img/img-01.jpg 1x, ./images/what-img/img-01@2x.jpg 2x"
      src="./images/what-img/img-01.jpg" alt="процес кодування" 
    />
</picture> 


    Приклад завантаження картинки без тега picture

<img 
  srcset="./images/what-img/img-02.jpg 1x,
        ./images/what-img/img-02@2x.jpg 2x"
     src="./images/what-img/img-02.jpg" 
     alt="maketing"
     width="370"
/>