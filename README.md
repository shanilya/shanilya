 👋

<!-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mere aalu ye aapke liye </title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        .slide {
            display: none;
            width: 100vw;
            height: 100vh;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            font-size: 2rem;
            color: #fff;
            font-weight: bold;
            padding: 20px;
        }
        .slide:nth-child(1) { background: linear-gradient(to right, #ff9a9e, #fad0c4); display: flex; }
        .slide:nth-child(2) { background: linear-gradient(to right, #ff7e5f, #feb47b); }
        .slide:nth-child(3) { background: linear-gradient(to right, #6a11cb, #2575fc); }
        .slide:nth-child(4) { background: linear-gradient(to right, #ff512f, #dd2476); }
        .slide:nth-child(5) { background: linear-gradient(to right, #1f4037, #99f2c8); }
        .slide:nth-child(6) { background: linear-gradient(to right, #8360c3, #2ebf91); }
        .slide:nth-child(7) { background: linear-gradient(to right, #ff4b1f, #1fddff); }
        .slide:nth-child(8) { background: linear-gradient(to right, #30cfd0, #330867); }
        .slide:nth-child(9) { background: linear-gradient(to right, #fc466b, #3f5efb); }
        .slide:nth-child(10) { background: linear-gradient(to right, #ff758c, #ff7eb3); }
        .slide:nth-child(11) { background: linear-gradient(to right, #ff6a00, #ee0979); }
        .slide:nth-child(12) { background: linear-gradient(to right, #ff416c, #ff4b2b); }
        .small-text {
            font-size: 1.2rem;
            font-weight: normal;
            margin-top: 10px;
        }
        .navigation {
            position: fixed;
            bottom: 20px;
            width: 100%;
            text-align: center;
        }
        .nav-btn {
            background: linear-gradient(to right, #ff416c, #ff4b2b);
            color: white;
            padding: 12px 24px;
            border: none;
            border-radius: 30px;
            cursor: pointer;
            font-size: 1.2rem;
            font-weight: bold;
            margin: 5px;
            transition: 0.3s;
            box-shadow: 0 4px 15px rgba(255, 65, 108, 0.5);
        }
        .nav-btn:hover {
            transform: scale(1.1);
            box-shadow: 0 6px 20px rgba(255, 65, 108, 0.7);
        }
    </style>
</head>
<body>
    <div class="slide">To mere bhole aalu this is for u<br><span class="small-text">aaiye dekhte h mazza ayega..hehe!</span></div>
    <div class="slide">Mere best friend banne k liye thankyou<br><span class="small-text">aapke sath baat karna bahut pasand h aap jante i can't live aapse chugli kiye binna</span></div>
    <div class="slide">Aapki smile pata h mujhe bahut pasand h <br><span class=pura chera glow karne lagta aapka ,hehehe </span></div>
    <div class="slide">aapse pura din baat kr lo tovi kaam h mere liye<br><span class="small-text">Chahe kita v laadai kr le jhagra kr le aapko chor k to nahi jayege ..indeed</span></div>
    <div class="slide">mujhe laga tha koii friend nahi hoga mera pr aap mil gaye uske liye thankyouuuuu<br><span class="small-text">If perfection had a name, it would be yours.</span></div>
    <div class="slide"> Aapko appricite karna tha isely meri tarf se aapke liye<br><span class="small-text">ye website i hope aapko mera mehnat samjh aa jaye .</span></div>
    <div class="slide">Aur meri pyaari baiko merese milne jaldii aaiye<br><span class="small-text">kyuki i really wanna spent time with u</span></div>
    <div class="slide">aap par roast maat kiya karo mujhe ..par kr lo haqq h aapka<br><span class="small-text">aur merese gussa hoiye isme issue nshi h pr jyda der tak gussa maat rahiye</span></div>
    <div class="slide">i really like your eyes jab bakyti wala baat krte to badi badi karte kaise <br><span class="small-text">Your heart is as beautiful as your soul.</span></div>
    <div class="slide">thankyou for healing that u had not broken<br><span class="small-text">aur aunn lijiye mere aalu h mere hi rahiyega bass baat khtam</span></div>
    <div class="slide">Your are my baiko my aalu forever and ever<br><span class="small-text">aur bass ita hi bona tha.</span></div>
    <div class="slide">MAY MAHADEV GIVE U SUCCESS AND A LOT OF MONEY<br><span class="small-text">a small try hope it made u smile form your gober'lilar but yours</span></div>
    
    <div class="navigation">
        <button class="nav-btn" onclick="prevSlide()">Previous</button>
        <button class="nav-btn" id="nextBtn" onclick="nextSlide()">Next</button>
    </div>
    
    <script>
        let currentSlide = 0;
        const slides = document.querySelectorAll(".slide");
        const nextButton = document.getElementById("nextBtn");
        
        function showSlide(index) {
            slides.forEach(slide => slide.style.display = "none");
            slides[index].style.display = "flex";
            
            if (index === slides.length - 1) {
                nextButton.style.display = "none";
            } else {
                nextButton.style.display = "inline-block";
            }
        }
        
        function nextSlide() {
            if (currentSlide < slides.length - 1) {
                currentSlide++;
                showSlide(currentSlide);
            }
        }
        
        function prevSlide() {
            if (currentSlide > 0) {
                currentSlide--;
                showSlide(currentSlide);
            }
        }
    </script>
</body>
</html>-

