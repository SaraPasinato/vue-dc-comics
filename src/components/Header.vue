<template>
  <header>
    <div class="row container">
      <!-- logo + nav links -->
      <div class="col">
        <img src="@/assets/img/dc-logo.png" alt="logo dc" />
      </div>
      <nav class="col">
        <ul id="list-nav">
          <li v-for="(link, index) in links" :key="index">
            <a :href="link.url" :class="{active: link.current}">{{link.text}}</a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>

export default {
 name: 'Header',
 data(){
   return {
       links:[
        {
            text: 'Characters',
            url: '#',
            current: false,
        },
        {
            text: 'Comics',
            url: '#',
            current: true,
        },
        {
            text: 'Movies',
            url: '#',
            current: false,
        },
        {
            text: 'TV',
            url: '#',
            current: false,
        },
        {
            text: 'Games',
            url: '#',
            current: false,
        },
        {
            text: 'Collectibles',
            url: '#',
            current: false,
        },
        {
            text: 'Videos',
            url: '#',
            current: false,
        },
        {
            text: 'Fans',
            url: '#',
            current: false,
        },
        {
            text: 'News',
            url: '#',
            current: false,
        },
        {
            text: 'Shop',
            url: '#',
            current: false,
        },
     ],
   }
  },
}
</script>

<style>
header {
  background-color: #fff;
  height: 12vh;
}

header .row {
  height: 100%;
  justify-content: space-between;
  align-items: center;
}
#list-nav {
  display: flex;
  justify-content: space-between;
}

#list-nav li {
  list-style-type: none;
}

#list-nav li a {
  text-decoration: none;
  padding: 44px 20px;
  color: #000;
  text-transform: uppercase;
  font-weight: bold;
  font-size: 0.9em;
}

#list-nav li a:hover {
  color: #0282f9;
}

.active{
  border-bottom: 4px solid #0282f9;
  color: #0282f9;
}
</style>