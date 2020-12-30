<script type="text/javascript">
var images = [],
index = 0;
images[0] = "<a href = 'https://www.computerhope.com/'><img src='https://www.computerhope.com/banners/banner.gif' alt='Visit Computer Hope'></a>";
images[1] = "<a href = 'https://www.computerhope.com/history'><img src='https://www.computerhope.com/banners/banner2.gif' alt='Computer History'></a>";
images[2] = "<a href = 'https://www.computerhope.com/'><img src='https://www.computerhope.com/banners/banner3.gif' alt='Visit Computer Hope'></a>";
index = Math.floor(Math.random() * images.length);
document.write(images[index]);
//done
</script>
