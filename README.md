# Ex.05 Book Front Cover Page Design
## Date:20/02/2026

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
book.html
```



<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>3D Book Cover</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <div class="book-container">

    <div class="publisher">KHAN BOOKS</div>

    <div class="branding"></div>

    <div class="title">THE QUIET LANGUAGE OF THE HEART</div>

    <!-- ✅ Center Paragraph -->
    <P>   This book explores the silent moments that connect
  people in ways words cannot explain. Through kindness,
  understanding, and shared memories, it reveals how
  the strongest feelings are often the ones never spoken.
  </P>
<P>
  In a world filled with noise, the most meaningful emotions are often shared in silence. A simple gesture, a thoughtful glance, or a moment of understanding can speak louder than a thousand words.
   </P> 
   <P>
  The quiet language of the heart reminds us that true connection is not always spoken. It lives in patience, compassion, and the small moments that leave a lasting impression on our lives.
</P> 

  <div class="description">
     
    </div>

    <div class="edition">SECOND EDITION</div>

    <div class="author"><b>IRFAN KHAN.N</b></div>

    <div class="image-frame">
      <img src="C:\Users\admin\Downloads\irfan.jpg" alt="Author">
    </div>

  </div>
</body>
</html>

```
style.css
```
body{
  margin:0;
  height:100vh;
  display:flex;
  justify-content:center;
  align-items:center;
  background: linear-gradient(135deg,#6186ab,#407c85);
  font-family: "Segoe UI", sans-serif;
}

/* BOOK CARD */
.book-container{
  width:420px;
  height:600px;
  padding:35px;
  position:relative;
  overflow:hidden;

  /* Different curved shape */
  border-radius: 60px 20px 80px 20px;

  background: linear-gradient(145deg,#4e7387,#538785);

  box-shadow:
  20px 20px 40px rgba(53, 79, 91, 0.25),
  -10px -10px 30px rgba(143, 196, 234, 0.6);
}

/* publisher */
.publisher{
  position:absolute;
  top:25px;
  right:30px;
  font-size:13px;
  letter-spacing:1px;
  color:#eaeaea;
}

/* branding */
.branding{
  text-align:center;
  font-size:22px;
  margin-top:40px;
  color:#ffd369;
  font-weight:600;
}

/* title */
.title{
  text-align:center;
  font-size:28px;
  font-weight:700;
  margin-top:25px;
  color:#635656;
  letter-spacing:2px;
}

/* subtitle */
.subtitle{
  text-align:center;
  margin-top:10px;
  font-size:16px;
  color:#f1f1f1;
}

/* line */
.highlight-line{
  width:70%;
  height:2px;
  margin:25px auto;
  background:linear-gradient(to right,transparent,#ffd369,transparent);
}

/* description */
.description{
  position:absolute;
  top:52%;
  left:50%;
  transform:translate(-50%,-50%);
  width:78%;
  text-align:center;
  font-size:15px;
  line-height:1.7;
  color:#f0f0f0;
}

/* edition */
.edition{
  position:absolute;
  bottom:85px;
  left:35px;
  font-size:13px;
  color:#ffd369;
  letter-spacing:1px;
}

/* author */
.author{
  position:absolute;
  bottom:35px;
  left:35px;
  font-size:17px;
  color:#ffffff;
  font-weight:600;
}

/* image frame */
.image-frame{
  position:absolute;
  bottom:30px;
  right:35px;
  width:115px;
  height:145px;
  border-radius:15px;
  overflow:hidden;

  border:2px solid rgba(255,255,255,0.4);

  box-shadow:0 10px 25px rgba(0,0,0,0.4);
}

.image-frame img{
  width:100%;
  height:100%;
  object-fit:cover;
}
```


## OUTPUT:
![](<the quiet language of the heart.jpg>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
