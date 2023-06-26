<template lang="">
    
    <div class="container">
        <nav class="quantic-navbar">
            <ul class="navbar-items">
          <li class="navbar_item"><a href="#">Наши премущество</a></li>
          <li class="navbar_item"><a  class=" dropdown-toggle" href="#" id="navbarDarkDropdownMenuLink"  data-bs-toggle="dropdown" >Наши курсы </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDarkDropdownMenuLink">
            <li><a class="dropdown-item" href="#"></a></li>
            <li><a class="dropdown-item" href="#"></a></li>
            <li><a class="dropdown-item" href="#"></a></li>
          </ul>
          </li>
          <li class="navbar_item"><a href="#">О нас</a></li>
          <li class="navbar_item"><a href="#">Коворкинг</a></li>
          <li class="navbar_item"><a href="#">Бесплатный урок</a></li>
          <li class="navbar_item"><a href="#">Работы наших учеников</a></li>
          <li class="navbar_item"><a href="#" class=" dropdown-toggle" id="navbarDarkDropdownMenu"  data-bs-toggle="dropdown">Карьера</a>
            <ul class="dropdown-menu" aria-labelledby="navbarDarkDropdownMenuLink">
                <li><a class="dropdown-item" href="#"></a></li>
                <li><a class="dropdown-item" href="#"></a></li>
                <li><a class="dropdown-item" href="#"></a></li>
            </ul>
          </li>
          <li class="navbar_item"><a href="#">Отзывы</a></li>
          <li class="navbar_item"><a href="#">Контакты</a></li>
           </ul>
        </nav>
    </div>
</template>
<script>
export default {

}
</script>
<style>
.navbar-items {
    display: flex;
    align-items: center;
    width: 100%;
    justify-content: space-between;
}

.navbar-items a {
    position: relative;
    text-decoration: none;
    color: rgba(255, 255, 255, 1);
    font-family: 'Montserrat';
    font-size: 18px;
    font-weight: 500;
    line-height: 30.584px;
}

.navbar_item {
    display: inline-block;
}
</style>