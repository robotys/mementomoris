mementomoris
============

Event Stream Slider

Khas untuk memeriahkan majlis secara digital. Biasanya setiap majlis ada projector yang akan tayangkan slide. Namun semasa idle, tiada apa yang ditayangkan. Contohnya ketika majlis kahwin. Maka app ini dibina khusus untuk semua jemputan turut sama memeriahkan paparan projector dengan gambar dari instagram dan tweet wish untuk pasangan pengantin.

Cara guna:

1. Buka laman web mementomoris.com
2. Signup with twitter and instagram
3. Specify hashtag and user to fetch
4. Pick template
5. Input title
6. Done, open slider page

### Dev Notes:

All things is local. Pics sedut daripada instagram. Setup just for that pc+browser. Lain pc lain setup. Boleh save settings and upload kemudian.

instagram api:
> https://api.instagram.com/v1/tags/hashtag/media/recent
> https://api.instagram.com/v1/users/1574083/media/recent

twitter api:
> https://api.twitter.com/1.1/search/tweets.json?q=%23villagepeople

(%23 for # and %20 for @)

**LICENSE : MIT**