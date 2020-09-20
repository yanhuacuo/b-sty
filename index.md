---
title: 友情链接
date: 2020-02-02 10:00:00
type: "link"
top_img: /img/pic/moon.jpg
aside: false

---

<script src="https://cdn.jsdelivr.net/npm/jquery@latest/dist/jquery.min.js"></script>
<script src='https://unpkg.com/ifriend/index.js'></script>

<script>
    $('.flink').prepend('<div id="friend1"></div>')
    if(typeof(Friend)=='undefined'){
        location.href='/friends'
    }
    new Friend({
        el: "#friend1",
        owner: "yummymath",
        repo: "yummymath",
        direction_sort: "asc",
        sort_container: ["我的站点"],
        labelDescr: {
            大佬们: "<span style='color:red;'>这是一群大佬哦！</span>",
            菜鸡们: "<span style='color:red;'>这是一群菜鸡哦！</span>",
        },
    });
</script>


