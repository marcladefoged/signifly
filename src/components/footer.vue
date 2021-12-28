<template>



<div id="footer">
<div id="getintouch">
<a href="https://signifly.com/contact">
<p>Want to see cases specific to your industry? - Get in touch</p>
</a>
</div>
<a href="https://signifly.com/services">
<img src="https://www.datocms-assets.com/7718/1583767986-vbg40-chair-cropped1.jpg" alt="footer image">
<div id="footertitle">
<h1>SEE OUR SERVICES</h1>
</div>
</a>
</div>


</template>

<script>

export default {
  name: 'Footer',
}
</script>

<style scoped>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
#footer img {
    width: 100%;
    height: 100%;
}

#footer {
    position: relative;
    margin-top: 10vh;
}

#footertitle h1 {
  position: absolute;
  color: white;
  font-size: 3.5rem;
  font-weight: 800px;
  top: 50%;
  left: 30%;
  transform: translate(-50%, -50%);
  z-index: 2;
}

#getintouch {
    margin: auto;
    border: 1px solid grey;
    width: 50%;
    height: 50px;
    margin-bottom: 5vh;
    
}

#getintouch a {
    color: black;
    margin: auto;
    text-align: center;
    text-decoration: none;
    width: 50%;
}

@media all and (max-width: 576px) {

         #footertitle h1 {
            font-size: 1.5rem;
            top: 60%;
            left: 45%;
        }
}

</style>
