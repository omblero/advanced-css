advanced-css


<!DOCTYPE html>
<html>
<head>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body, h1,h2,h3,h4,h5,h6 {font-family: "Montserrat", sans-serif}
.w3-row-padding img {margin-bottom: 12px}
/* Set the width of the sidebar to 120px */
.w3-sidebar {width: 120px;background: #222;}
/* Add a left margin to the "page content" that matches the width of the sidebar (120px) */
#main {margin-left: 120px}
/* Remove margins from "page content" on small screens */
@media only screen and (max-width: 600px) {#main {margin-left: 0}}
</style>
</head>
<body class="w3-black">

<!-- Icon Bar (Sidebar - hidden on small screens) -->
<nav class="w3-sidebar w3-bar-block w3-small w3-hide-small w3-center">
  <!-- Avatar image in top left corner -->
  <img src="https://wallpapers.com/images/hd/smoking-tom-and-jerry-3d-4k-387r7h5797f3x8qm.jpg" style="width:100%">
  <a href="#" class="w3-bar-item w3-button w3-padding-large w3-black">
    <i class="fa fa-home w3-xxlarge"></i>
    <p>HOME</p>
  </a>
  <a href="#about" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-user w3-xxlarge"></i>
    <p>ABOUT</p>
  </a>
  <a href="#photos" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-eye w3-xxlarge"></i>
    <p>PHOTOS</p>
  </a>
  <a href="#contact" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-envelope w3-xxlarge"></i>
    <p>CONTACT</p>
  </a>
</nav>

<!-- Navbar on small screens (Hidden on medium and large screens) -->
<div class="w3-top w3-hide-large w3-hide-medium" id="myNavbar">
  <div class="w3-bar w3-black w3-opacity w3-hover-opacity-off w3-center w3-small">
    <a href="#" class="w3-bar-item w3-button" style="width:25% !important">HOME</a>
    <a href="#about" class="w3-bar-item w3-button" style="width:25% !important">ABOUT</a>
    <a href="#photos" class="w3-bar-item w3-button" style="width:25% !important">PHOTOS</a>
    <a href="#contact" class="w3-bar-item w3-button" style="width:25% !important">CONTACT</a>
  </div>
</div>

<!-- Page Content -->
<div class="w3-padding-large" id="main">
  <!-- Header/Home -->
  <header class="w3-container w3-padding-32 w3-center w3-black" id="home">
    <h1 class="w3-jumbo"><span class="w3-hide-small">I'm</span> Tom.</h1>
    <p> Web Designer.</p>
    <img src="https://dthezntil550i.cloudfront.net/we/latest/we2010171905205230016120984/1280_960/68b06aaf-3152-4212-832c-b61d9156d72a.png" alt="boy" class="w3-image" width="900" height="1008">
  </header>

  <!-- About Section -->
  <div class="w3-content w3-justify w3-text-grey w3-padding-64" id="about">
    <h2 class="w3-text-light-grey">My Name</h2>
    <hr style="width:200px" class="w3-opacity">
    <p>Thomas Jasper "Tom" Cat Sr. is a fictional character and one of the two titular main protagonists the other being Jerry Mouse in Metro-Goldwyn-Mayer's series of Tom and Jerry theatrical animated short films. Created by William Hanna and Joseph Barbera, he is a grey and white anthropomorphic domestic short haired mute tuxedo cat who first appeared in the 1940 MGM animated short Puss Gets the Boot.The cat was known as "Jasper" during his debut in the short however, beginning with his next appearance in The Midnight Snack he was known as "Tom" or "Thomas"..
    </p>
    <h3 class="w3-padding-16 w3-text-light-grey">My Skills</h3>
    <p class="w3-wide">Photography</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:95%"></div>
    </div>
    <p class="w3-wide">Web Design</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:85%"></div>
    </div>
    <p class="w3-wide">Photoshop</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:80%"></div>
    </div><br>
    
    

     
    
    <!-- Testimonials -->
    <h3 class="w3-padding-24 w3-text-light-grey">My Reputation</h3>  
    <img src="https://www.redwolf.in/image/catalog/stickers/jerry-face-sticker-india.jpg" alt="Avatar" class="w3-left w3-circle w3-margin-right" style="width:80px">
    <p><span class="w3-large w3-margin-right">Jerry.</span> Cartoon Artist.</p>
    <p>Tom helps us in web designing.</p><br>
    
    <img src="https://i.pinimg.com/originals/5c/26/52/5c265259f626f75da99e9fb79c345ab8.png" alt="Avatar" class="w3-left w3-circle w3-margin-right" style="width:80px">
    <p><span class="w3-large w3-margin-right">Baby Jerry.</span> CEO at Company.</p>
    <p>No one is better than Tom.</p>
  <!-- End About Section -->
  </div>
  
  <!-- Portfolio Section -->
  <div class="w3-padding-64 w3-content" id="photos">
    <h2 class="w3-text-light-grey">My Photos</h2>
    <hr style="width:200px" class="w3-opacity">

    <!-- Grid for photos -->
    <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half">
        <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAARAAAAC5CAMAAADXsJC1AAAB4FBMVEX///98gYX+/v7MgwP4q5n60nrIyMjd3dwAAAC2tbV/hIj/6cLPhQPOzs7Kysr/75jl5eXy8vJhYWHw8PBXV1f/sJ6NjY2/v7/4+Pj/7sZ1en6tra1ubm6GhoaUlJRQUFCgoKBna29+fn4yMjLW1taenp5kZGQ9PT12dnbhEiJeYmanp6dobXFISEgvLy9QU1byzXkfHx+AUwiucAfZiwDGewASFRgmJyn/+Z5HS04dHR2YWwCVYAeGUABlQgi3u7+7cwDEqGWweGvfl4ddZHEAhgCjal1YLgCQWwBILwckAABpOAASAAClagZ3QgA9KAm/r5Phzqx2TQqdhU+UVQA5Q0hqRT2OZFtvUk1USEdJJx5WPTceMDaQXFA1KihcNi17TUFDLyuhll4yMB/g0YNYVDVqZEAOFCMbGg3Mv3ktMTyto2eLg1TIu3dfXlBUW2dAcCtvd0Z5dVlhejsNuA8Umg8ARwARYw8afBT45JQGKAAudy4cUBsYlA0+ORkufyE2YzkANABIRTRAGgBWNABJHgArHQZ0X0eijnlwUCeEdmhJMh4AGjGBWSJsUjTYzrwxEACjlXvIt5mXZkmHDRa7ER6aDxpaCxFfQB3KESAxAACHaTTRrl6XeVejloqfgT2Ei+UIAAAgAElEQVR4nO2di3saR5boG5CgaXXjBlp0i7dooDHQYPFQG0lIRJpYUhT0wJadycOb1yaZ3ayyu3dndjJz7917bSW2letc25PZ9Y4zk391q6pf1U2DAFnkm291vs+yhFrQ9ePUedWpguB9V4JJjvARV4KJ/wqIVa6A2OQKiE2ugNjkCohNroDY5AqITa6A2OQKiE2ugNjkCohNroDY5AqITa6A2OQKiE2ugNjkCohNroDY5L8LEDYeD4504VSBCLHSz4SfXWLZCjvKlVMF4q8URdE/vdczRRHA20EKI1w5VSBBkqJc1ZUCP5r2vj6JZwm3m/ClRrh0ujaEVygXRZVbS2I86c+G3VN6WaYAeAAi+RHGOmWjmhMplwswcUUXq8eiUgnlRprYFxTRrQJhIudfO20vk16BRFyIChBXcSV06XoSiyEegAp3/sVTd7ve5aiORMVSrlw2EUnlAYiEzr94+nFIMNXCibio8ii27gIS879GIO7IJfAqLbssRKq51/8amBgK4ibi5199noak5FQhxrCCrtZuQWCzAT6WS0aAJNN+r28U724VH2klsnKZWurNGQoSTpx/+XlABDEoeHOZkAwkleK4FBfPJJIlP+9lstks4+VLiTwXHzcAzS5bZo1rZXyoI0sqaADxe8+//FwbEqycF1r6hHhRqiQdxyQEnYea0+wIRalmBJn/cHjA1RcRljNnTN5ivr3cUr7/9UYwqgkxC766nQX8JilGgQMtkknLXzG5uKwolUpFUeR4jrF7ElHFwVXA30aLVVJUVpSlFRKIwr3W4D7iNWcMbkKCEngL2X4PN4qXCRekUhh91w8EGBEmpQ6uqoS1PxBiIfK4qEYaUKKLrRXZGoJ5WzCKJyvloiS1iuXyYlWS5FQczcbs5MPvl2XjrokMNtSsDG7WTWT7rMpobtfNx+WM32dNQdCLJKrlsm4bo6Q2Zp4k727euvfOL4+rZXVWwBCsIsWw90OkqktkpdUquxZlSebkEYLISSRbMBVENh9OZ7T7l+1/MHocwvKRfKoihfKFTCRXivHa3yUX1QFTiIg+J9nEu1vz8/MzW7fee7+oGQrKxS0nDKacAvSjSC2KpLxYjrooZQSDN4FksgYQzhxpPqbpDRGy55ljB2YCy/p8voC/lIzLXCadiy/CwS4p8iKAsmjGWELxg/mZmRkA5db9KqWHpYvLGcSMUYpUGZiPstRqVYEcSxKZuYy0pmLw4AvGrVUY49GC/UUvFKmG00vo7Qf2g+Q4CXwvxczfxv4GEoFMNitlI4MpL4MwrFBxGYx0cRWV1GtHwqe1oRPCij5fgxXWdDzchTUEijcTT2tPlAapCbVIcnBoRdFF4UUYXiMyMz9zt2oEHhSnrJStYYjOJqrEnF9wYpHdOhBON9WsKJjOAYSxNpkACCsmfWEmlGALMhcPhJUoJZOqIXEp0XIeu7L0gUZkZn7zfXPgLqBLDkDgr1qv17byepRKlPSgICu5MR7hvP1PxgcSkFUliMhQwWNyWI5K+jtOKVERd5rVrRmdyNZ9M8sdgAMRSU8y8EEi6baT1Y2bn8ODByLC2P9kbCBZ9RmJcAj+D+zIEktib/iKC1fCsD5poLxnmShR1TNZcUhliey7xTFEsEaecc3FADKaAYlkLDzcfV53bCBuUXPgmbAOvyKZAwNuo4rbgfKWCWQeJxJtUa2KUrYCKS8qlGt50vDdH+LicS5ujsef0CdMXFVbdypmiS2JUKKvujsukJwWCYNM2lC7KvZOU1J0CQu/fB9iKjL/UdS4rOoqg3QmauFBFcsS8MQj5OgOEpP86HWDeT349Mk6D6/6ECOyVh6RDCOGbc8zLpCCmjsS7owZAUqWqSCWM9j1FQzIzIxieN8WJfUbkMVFwHayYkAcGk11eqTVgIOt6AYEBCOQVNwyXcDDCaDLfOmCQPJBu4YAxbPaAZeChRMUNmeArzGUqUopWkhvURFgjUCaqDguUwy7UTaPuY54AI5f0b0rLJkRQkL22XiEeJDMBOzFqfGACIUV3U5hWXUC13yqXHVhNUH+Fq4i8/cNFXFVwNijkmy1tPCZQMbbFx1AGVb/C8cxIIKI6jiGCksEU+AYG46sDOcPEeMvAiSg+NxaskQkfcYLxq2KL1It81XYDy1ANk2HBCZaFKb7ktULUy2yGnNaQAln+h/DaGHmgUgJYUkwpzSZh8m6xXq4MxHVWRYuYkMC0EmFVO9CCMj9oifFbQgF5wwlmn/0rsWIzBxbDDAEQlrL8C6ySsmEQwyfHRrFmjME3FAux5nRF+GHb48FBxHjNH5EX4F7DCDuJVhBECTEVEuWEBoF86YccCCLVNksM9y3AJm3GGCSlFsKQIIRAVlRlBKdcpr08ESHNV0IwePRFxGz+RbCm+J1e8v3UR4DSNqvjr+Qz0XAxCGYfFxOQfNXMcYTlYDfBK6CkoxnTelAtlDy+x4GpEzC4Cwq6USoVhTmzSApclKG87yxICf1YWZjVnthNR6pEoGZlwsASel+jfBlgX5qj1q8THkZJDXR5WLUnDScrht334MVkgqmDEU1A4p+/AmpmeUWFSWBvkUdBs+a7mDQwhavpSkEmxxQ8QS3nk+agIiI3aSOBcRcAEMSDAsaobRRMyuiGaEsyqKkVx8MIJvHx+988JElNlXh/OLTa39LakYF+NxPQ0DB4PP7vHwpmYinJAlWFxU5xWWSfiYsxAYG976QpiIFRyDQO0cEjIffwU6PAcSYmOjvUqE4V1CNqk9fiqNaZdXNwJqz9o6GDPNxr0pZI1NNfvH1tZuffY6UpUq1vrj5qzIlFuSKeFwtlqPRqFYyga8RLRdbkkhKqUKJd1wO4rSwMe4EhHAXQFhp4iCSBYenGAOIsWZcCgblBAPEXxGQpxF1IGotvYJqRqL6cmUz33332J7N6UAAkb8Dv1ssU59/efPmCQCrFY1MW6uyhKjLqHdAUlZSmVLAamlzARVIMttPhBBgCxGmLbKj2xrH7aJQxk0EU2yFZ7xAAn7O4ne16FP1OlQVRVKRLV1Bjh3LQmjKQCIwtSlSJFCXj13cou3SqJkvtbQKLYXWL8QlOZ/0ZzV1AWEWGm3QSUUEAZvz2XzeuWtnHCAwWYSL1WExEPAiYQow1yPy+m1LGBBABNrGjc151YSQv3zPuS5U/tU1ROQrCnjsz25eu/arXyzarqQMb03J1l9ALOWqtKLImZI3XOL19MXRhug02Jw0sIA7XuheEuN5kkjwGg9vwAtVhChod1cs4kDADAJJRFAticy/szk//74NSLkMZ0X0728iIl/+gqp+DrXl61a0arkS+mP7d3YsrjJ3vEw6TBUrE2B5k5V4v3OZEAjw9sBVFRivLgwHAlciok1wCf1PGa6VIt1GSWQecBGtw5RaVVECIciXCMi1m//webSIvjl2yZYeEmMGAR5Dqm1Uysl2WHCEk0p8+HrHBDVVMhYwgARyIFojcqoz1UhQYku/xSJw+kEteN/a2qraJgIF22XKFKcCuXbz76PczZs3r908cVmygWLR4DHADOmEE07G1LQcWY47d/VnAiDpJAaETwAgpUV0Q2XN3kmSoeHL4HqvNmnufdQ/GkquRKmvPlWBfHrtK+7rf/ynazf/GaLVvYzJwzVMP6BEl5k+IERG0OJJn5yxZ3KvB4hbMqeMlwkZQNQoBN6XCQTlvRvvggkzP7/5vt13wCuiStH1MVSRm//05v/guC//5V8+BkCAGeIkVJw3eIAYfygNxC5mBwKrQOpk4bgRcEy2LlPwmyrCpAg9VDVshxqOwP+jURQLstW7tzY/bFFFzuEdplrVKtSPr99889di8Te//tff3/ySUqqVoqsIchyYKmqDtVQqHVVFitjdLZFLqjwi0ojjnAQIg1vVlGFUy0bAqrfDRFdcWk4TZKRjWBBqOSxBUK1j6Gd+9WvyN7+P/ua35G+//pJqoRXBohjVZglQD1y9qK+OHYEQOR9OhFB5EERAGnnleKKVOwl3MwBIBt2kMVGihkmMVkg182Hj2vvbcpo2onQNAfnd76n/CYB8+qVqPqiiQqo4XK0qRpKK3q+vFm2xLHo50pfCl6GIQgzxiI/QSnUhIHEjEFGBqCUzw9tGzViBWlRC6XSmYhSBqKKTkijA8379Jvm7f6Sq/4t88+P/rSiw2uxqLZfVlWNdT1QE0QOa7rwP18iLRdg5oGU7QNUKRFhiCD39zMpQXwh2ZZylnomA+E0/g4wqNA3GZLe89yDQkJaXcG9JueS+gJWqHv/DzWv/9q+/+T+U67e/+12Shak8NBpVGLkVW1FKi0iPK4okc6QHACkHeN7vj+UiGZAPVxSxBTJBqgVcSgymm4I76OdQok9kyZGM6YWAsCFjzjB5Qs1lqIqTwYxKisxxttr6otwXTkhffXrzs/+bKuQlUlvdLShwFb0YrVZR05W0JHIRkPyDN3+jTXvojnURWGAZfzIuiyQJ83six8UTPIpACF9lvIWvydohDCMSgIXEMLAeWLSAzekqeGO5ZftvQMbaKlsgUSIlPVAXmsIxiSR9bMInAQ6yuAhs9bJUKGXNYd2nPR5Ps+x4Y6yXN9fuUCwmjtknPRmQlAEkBvSSCbUo4FkcNCQqlSVusT/9AEjkIp7dt8SEOgIvGeGZEMyTFWAipIqYT9sa9rxtCIQe3P7MZqSYji/puKAxTCYDktEjkUAS5G85f5GqJjKcQxxJScuVaj8oiKSMJoOuIWqdkwiSPOvjyQLhiyhAuyoO/XecBwp9OnRUXCpR8pcK8vgNjZMBKZX0/D8DbjmeKbtCDBNIVPuJkMVq0TmKgrUexAS2YsX11Dy1HKqQZAyoHZhuLQf3ENwGFgQA2Uf5e5hlB0wJNuDNTrJPaTIgfEQHwgHljLMh0QseYPyyfdDQMkarxWi0XIYtZZYFnGJVksDgRVFcUbtZEBEmT5IKXGgEE85paWpjlfbUAJDVDcGfh8s6r7WJc1Ig2QxjBKqEL00kkmoFLZCy8oDaAZyKopBVripVKpgtLStcGQUQUpjl+VgymfRqSRgL/CQbO6bw5S5Top41skfTdJfc234Wf/2b1SYD4oszWoEoDkxIOMtpfAARi/OogGBdhB28rmoLdimWWxUjY9Vy2aperDELfNkSES6FqpJjPPXROllr0PXTWu2XG5MPe7BMBkQPRAKlNIgYwhUjLAnw+GaYxWqxoukEmCGyykSScONLVdQlHrfXbCgFTyrAZi2nVw6TvVrDs96rrT8ctWUxONYIJwMiaH6XKfiIIMd5sew3Ya68UIt4sxUAs1itQlfUMqN3MGPA2H2lRMQs7RBLwDKkgTtxMJfC/Z1ao767tltvdLXOjtA5gShPTgEIITOGCYmROaw+onW+a2JzxNCqLnJcUSJbcMUFmNpiUQyV0l4YNhg8BGgqWef2B2ltt9Fbr63TwNXAECNMuvmhXQFEYYRdVLhMCEQNVQPwZkQskIeP+S07yBxCE7VJd6m4CFIzkAeimWEt+fngPZUcOjRdbbK2W1tfawCrSu+7+HTJ1SKUIfcZXBq383VCIOqUgVEIYMIFvLiKJPBUTukD4oJrDKipW6VVTFiKOgSfBXMgzEsOPJjtXS8gUm941tZP12vtZ+Tqzunb5OAxZ8ebLlAmBFJABQA4Y5YFwp9gLEQ4bPRlpU9HqBW1mSoqynBKUa2cRUG8JZLk4iWnlOzbvdLy2q6ns36w0wQq0qh1wdRZ774lDbCv/vESXfVvJgPih4EHE8+ijukIyeA6Eghg8RnI4/qS/SIqdhSrrSVyBfrkVsKyxMgN2pMYab+vdA/qp+sdmlbjdxiynq51m88cPXBypM3+9pFNBsRNJhkmkSRg6wmhRPMWFQG+Fxu+3FcnoSqhDFcWQ1kmwOc4WDzljDsPcH1NTrqEv+mR9bdJA4cq9G655mlsJ/uvj0zCY+LdEKWlTN6fXYKxE7CiUtpGRDa0oVWu9M2ZxUI2uaiHGSAGU5bJUtaX5dMhOTc49Cw2d5vfflunO982MSL0I8J91mns9RGJLNncdpDPLDmt91tl4u0haS7DRdBLVuD2H95iWANeTrOsIHIXpT4VWWJClrg8nI2lc+kYM+wtze7RjbXeOvC4zQMcyClw0clO4xubaU1YA/9sQknlAiOozAX2y2jPXkKdG6LXSoSJtKL6Tqqlcp+KiH27EM6VUBOMvnfQOF1rrHVNInQNNnEmOo23LJF+BI9zfRkS9a6OIuMDCQdiiUK8EPGrc51dVvuipICFiJfxJqpFLWHpqy6iFb3xhN2HFvSgRtO13SZQEx0JXUcJ74nHQ2JTJGHWj9ylpdCQxW27jAckGAulMiVv1sey2VgI7kYKrmhDjIq8xY4AJWFi8VYRFsW5viJideydQoUmmh/rsJ66++3jP7c7GhL6QQh4XaHX6JpVxYQRngYzK44efKCMAySb4njcUIWlsKCY9UGxxFiVBDGJJBKZjNgXjJxX2hNiZa6I7WwN76HCYZeEetJtgcwn9kRFQq+iNiZmtfGNPmkSetOeLy6Pu9tkdCBMKgI9gBYtwO8IdwrPXKlW3mtVEpUJkJy9lkaJw89gcD1cbXqa3W1ZDzAi2ugPoPmgSRK6i3RbfewMlZYydOd98KDgJtLafMlKqfEN5KhAglxGwBsLZLgL1q1YzwIpVxKMXUtUg9KnIuVhe8l8B/VOt1v3NBr0nV3XBtSTg4ZmNhCQdZKERtLXQ2rTKUEVCd9pPMxmW98cLIa0O5Yn8RcjAimJeMMaKxWjYtXLkfayMlVUCrwDEybSZ0Ucy2GqZN/uvXdvc/PeO9+tdxuN5ur2s8pXB7VabQ3pg2ZIYRWWCD5BP95BjV1/oTv/75tmo0m64JMkyVH9yjhAgqVCKOMn3HIE75UWlmBLe7TaF3Gh9QVFTvjBLAkEVLcD/wc/2lMaShpYCw2TqMUXytbme70m1I1mp97tdg1f29glRbVKj3Sksc/AnR6dRqcBg5Q9HmR1DqHrxYEkZT8bZv2yaOlDITjUjVrti7c0JNSiJHKZHDxRA4jXH0vGU1zKHossDlyAbt012+MBk3dOYWAK830s+Oi4tAps9o5KJADt7s6Ox3MALpUyo/WCjAskp2VZQtDCw48sZNlhzQF1SrbEJYnjuFA+z6VSoXwhkvay8Kg5u4qQA17V+5Z1/8T81nu1hscm9FO9pzDXQT+3N9yJo7m5xwd1GkyoSdXjHCB6L7etfqN3XfbRcBVFJV5inHNxybZ+RykDXvh4a8Ym85u7HtpO5JHu8L5Hv2rcSfz/w6OFx3/boHvrntalAPFFHBukeQfVUI2HNOxQMr+tjZkqOmf5YdsGG0Rk5rs+Is0TrdOeWYWxWu3sjHKRR4dH7d0u3Xg2+cEsQ4CwzkDiDp2ilKu1kjynCr5i5+hYVSf4zX4gQL6z6ge0s4+0brozmu4dHskMmyRfLByRwOLQ25MfIjBsynCOQPptKUhkRjjysWRvynQ+eCjXN2NUQ3Jq2hG62TvYXT89+Nynro93vp9b+IJhSyTQkLMDtM45+XLeMCCR/ibHfiCw1ZQb6fVtBzFRVUeILkcgM/P31oxJswtmBawg1t+CLTFE8O25hTmyIJPk8sLRwnMQmtB7l6MhEVHLEq1TxopjUek7gmOAJG3BWdRxgSDqDGRm/jsdSNOoIDb2FOBuAy8W5haOnj8/ATNm4fDosAOmzKXYEH+O8Ofj8VCKtRaBDdUHThaYjpFXV912FVlyuu3CICD36na7CnzL6b5SOluYm5tbWFiYOwRgwA9tmv7E4YkF70h6PASIpK4xEratBQQ6SwaGHNVlboxCA9A4q4pQVfuuaigDpgzwvTv9QOgOpLEAaUAocwvPQSxSoztmISC8sYFitHBkr3vH6fVGB8JmHG0q4U1lVqSWpIgFfkzFFOyOximfGWBUgYZ0rUBQ7No5mzt6cfj8+fM5ROTwMSBTa7T1HDl71q537rR7vb12E8yzUY4YHAIk0Q8EKEsmDkaWnawZxWZFKNFBiWMObndr/Q/zM7u0hYWnvtNbP/3i5Pnh4YsXRy8AjqO5QxJqSrvxJ+2dotq0ITC+HyWeHwxEEG3bXYH4EmMXXHBx2+L3qENllflgvk85/kB77r401YKu76yv93a6IOIgHyyoAtTjwRkJrMjc0Z1mET0T+6BD49pUa48S0Q+xIXFtv5b61e1Px8XMxBVpVWK2jUHL/XoWvmsFsnV3a6YGGHTVvL/Xq52u79RVMKskCYkcScByLDwHP0AuL+ptZNlye1At6ghIt1ar9eqN/QtW3SuoosCivZ9EMpmdOIPEntLqZ4oOKe9HttzuHnkKcny6BpwtvUOu766pE4Cm298dLsOzA87OoFk9BN8iC3vYfAaexfcAOSW6h+pJ62t0o0F3Hoxwh0PT/0TeH8ujE0MIhz3Qk0hAsqlIfw9IaMYq81sf3m8CC9Cr977dbTa6qvelu5+AqKOCDg84OXxxeAK/eQGBPO9QwKHtq7EK/RBOm1qjW+s9OUmP0rI6vEDEkj61H5hIvKYTGzlLJkRV031XpK1uBhWKnjaatYNvm2tAL3rqQPfOgN1YeEBaBHmaV3vB7EvNetAv2ROoXQ2Q+oxY5z+nhMhr9evMGPsJhkp4yaYifVdYD9jY+sMmPBkOROuN+g60JSiCp3cfoGjsxMJjCUUj7b9LtrW8h277iEcAyBernc7eiBtEzqup8lKaT8dTr++gQqvrpVr9mifh+vFho9nbnN/8sAHGVT+lPZ01ZBRWn8PZcVaxAHmAbOqzU2Ppl44TySaI3jbYjY1Rs5vzi8wBnnk9vY8RKR8HdtnWQlPpvyXsUJr5e7DY8XRzCxnHA6j+cKSd5nMwY05eHFmAnEAgqXUjLaa7GwAI3Xw5zl1O79TuXAIubfGEdUnCSUXwg5y2gLsFBgCaUnoNflFVpHm4cPQAOBeVxA9//BOJnAxwwc+w+G3bTQjxR85nAQ+SqQFBcR4BG0oy1npzf23Vi8Vm85tqAIKGCYMKuoa+fX6I9OEx+cP16//+H9evv42AHC58j8X3zegE9zk1IGlebd0WfUTFqiL98WMRPw5us6el+5rjQEAazx4jCzpHXgfyww/X/x0AeQySmg6mICOF6naZGhBtMxzI8AjGEoxQZJ+JEu5bQvfNJzD2oLX0H1qTRm/7SE1wz36ARP54/TqYNIeP/7KKK8jwfs0BMi0g7pBewmfiRMayw7JoPU8Gzvjsu/jSzPzWS+Ra1OB9B4Squ136n1UNmSP/eB0JUJGjM5wHvT+RL5gWkLB5Ml7BSyhWFcFuIc3FRTCH/HfNg0f/UFPNyNqpmqfVe7tw8eVQVZEXpAFkIYWt39CdyT5P4GcAQijurIVI2ay/83ANPLbiI0o6kU1YP/Wgf13VnjZ21wGQxuqhWik7exsB+Q9gU7/Dbc1YztaU6dkQc63cJxMZPDyjKkbchw5AJQQpQMT0MxQQkNq9Dzt6WeO03ujUemudNoxFgKs9efs/kYLMzYHAzdNsqlnd6ljFPFOmBoTDDl4DCcGSJadZ0i5i41rFQWIJ5i31oK9btRoK3+/teGCcSvdQQ4Snvtbef/L46PAx0BHyT8CkHi0criJTo2Y74zexqTI1IDx2lBbhL7B4xdn4/BD9k0+AjhBEsPUBPHQEZXco6928t/mksbOjN+2iisijCtCRo+dnz8HkOVHDU6gn9N7Ep7JOLVKVBAsRv+WIkCU1ZMjoW/eJJKzFbNy/hQ5i0ZLema1b766vWyqrtGd9/0StMi8cwoYieq0G29C6E28umh4QFl8IJPyJAm5Gomq5xTxkO6y22PL5v7m1uQVk89bdZ60kEyTtixH0evP0MaoQncIEsPPG7AOQ3J1NfJtT/ASidNpCJJPCzAhVhFGUgFleoyDl8+coKlniUboqsagb0SLrjfpD+eST9uqXrzp0bXb2RrvRu5SFqtcuBR4nwnNYaYRCBzhha6fOFbo0SBAfOSzP0B6Q1N6enX3VfDULvq5eoFox1c+oiluIMKQEl7vULSIt10rWLWNWxmnNJgwTwfDLfiIoxwEoZp/8BL78RF3gHqf7oV3xJN6rxpJSuRjKHcdD1ayQq1Zkw6SCWMUpEcmjNRDhiRMRGurG7I0fwZcfL7Jdc8qfYpZM4b4mWCF5PxF2Ewmg44KkB7PgpgjHj4nQHnP/uc+OgIDs9qwuN9IXuMNpf6wbsxTDdwvFyQwTDgaDPn8kZHw0DpFLJ9JDn+VxHxG6+4YBZPYiBeDpf85dTgxjRPxkPpnIRGI+gjFPzCXI8z6y8C8du/fdv/HXCoQI4l2e4A4MF6k/FJZK5Hnn65bsS99PTB6zfzEuEzZKsfGaZy4VCJOL5HiHslXIixOxdVsQMZD2+MlPLK5TYBmvdXvRxr5lp1nnNgbk5Kz2NAGvjux1O507Y0VplwgkKCYDjDedlxJ9L8ENPLOQELg0vIJ/a+9BDpqXcHYjUvzum7399v7DIv5me5/h5cIaNmNm4WEJzYOw8KDToHeePl0d5zNaLhEIp99+FjvyRROJdSYCghPtfoLlb/bbe9vbe/urHboBhKYbHXz3JdM9XTdt6yuMxyxKapr5R3Rj9TMA6se37S8/RC4PSNj8/DC4AijHkzG084jNBkrxPJ7qYTxKmDUN5+Tt/fZqt7u62gZyB1aFsL2GG93Gqd6IR7d/xHjcUCts655G+2P0wBs//jTKMYhILg+IN2cxFITg42PAoWQykZJXIMJOPZ9EzrYmAf8mncyVNvhAYIP6YqfR2Hfpvyt16DVnBXkDbb5aqzfamiuG/70asVPz8oAwCbu1xMSNfeireQWbKw11CZHtBt3+SvshThvdzXQbtyCzt9ExVrXGqh6aIIP7aLTbvkQbUhlkONXROz1G8MMLfxsPabq7jN7rjbZpUpu4i5mdrak1euR4btx+47aqPj+NZkcuEUiSH0rEkVL/RxNYJXDDY2AAAAQ3SURBVPAMONvtQiC3u425mCcWHm/A1c9uV09uftS058+j3fVlxiFScFwiROm8NpTsATCtO9tNfPOMxaICawEVpNfYsUyj2R9fT3/IhUSQB34I6yAg8XPDyuw3jZ01PCSjV9+wjPxGDXZOdG3T6MaoRedLjVTDsqOpGMzD4VPF+iT9sDuMx+ztDuoZqlke/GnkIvzl5jIsvnfRjXmaAUAyI2wcDNwZymP2KV33NNcsCvIGNfqGxEtO7gTr6RcsnwaRSCI2wMekR1ieFtbx/WaWrF8dfIfu0TseXEFGNR9ILj3bzeblJJ/1+bL+HNwmH/CxQdbLOamNLzU85xCS3+/vRyi8FELX7TyAggCD2qNxBTn/jAxMppH++/yldLrkzxpDZ/GzpAnBG/D6cxlx+DYTIbIPj9np4OsydOe2nQewIM2ap9bFHM+rsboAfoZ6CEj7whYgMb+fZ4PDj9eK9Zrq5n9LZeiJnccN1PS8Vn+KTZjxugB+DiBp2wc0ImGGNaIHuS7eP6QrSO+GHcgruvN9sdNrYrnNKO3LmPwMQLwhp7yOGzJhsto2VdoCpN+gAou6WiDSzfXOx8ZDP425RjN9ILGUg9fFPkC6X5jthqYennp3YMQOJ8zOHTA/ks3mqmFCbhTHvL1pAwmGkv08wJiHtNL7tvXGZBCPmz4GLuPa5CnaM5VsYtnvk3H7qqYLxB3hsNq6+hD8EhlSZRdO9SpQfU3rdNdSGLsFeXIHFdRKHdrIY34cZVeZRaYJhM2ksuYHf4X9uVjAB0K0bEQZlvSHdKWga00LkFofD9VcZFdNIGOeDElMEYgvySVYbKmBS/kDfLqQkkKRobWsrFH3oG2tIdZ09sbTO7r5fNJY1X41XgiCZDpA3AkxAYdt2tClUV82YlqNmm1x6jOMx+0dgwcR62jmZVwPA2UqQFgFrlJjRjQ5egfYmd5ZSHdtvTJ054nmTG7cftrcx/K3k+ZPyIBM0pg5FSDWEjtBFMY43yOBjlNZ0/dBWIjQ3aevbt++/ardbL60DCP/EMyZn9KT3OtUcpmElQc3zu6s8GkHTJauNSYzQjPUe9eg2xnb7jG+8Py80yoGyDSACDI+XYJOu3WHiJuqrSEt6dF2BendX+10uu31gR9aN4FMZcokE6a39YrjWn71mCF69dRmQrq/DBJsYMP7egcwHS+T08/EZUMTtCo8QCcwb1gah2jP9tgx10gypTgkXAiVvN5SKj+Jcocf3Wmf+DR/o82WO+edXj6pTC9Szfpj3km7JVk4+qQRsjbqLyfsZD9ffpYC0WQS3m+oB5p1X17ObEHyVwSE8O53mp3V/fylfCaELn9NQAjBG9sYekzxa5C/KiDTkCsgNrkCYpMrIDa5AmKTKyA2uQJikysgNrkCYpMrIDa5AmKTKyA2uQJikysgNrkCYhM/EXP4cIv/vhKI/BdNkqo8cPQ5TgAAAABJRU5ErkJggg==" style="width:50%">
        <img src="https://qph.cf2.quoracdn.net/main-qimg-55a3251fd71180bffcc4896a89541943-lq" style="width:50%" height="170">
        <img src="https://i.pinimg.com/originals/76/05/bc/7605bc5477b276107594de0d51b7a654.jpg" style="width:50%" height="170">
      </div>

      <div class="w3-half">
        <img src="https://assets.catawiki.nl/assets/2021/3/16/7/c/a/7caa5dbe-64a7-4782-add5-4d7da7160cfa.jpg" style="width:50%">
        <img src="https://i.pinimg.com/originals/3a/6a/de/3a6ade821335be18a9933351f20e8d09.jpg" style="width:50%">
        <img src="https://resizing.flixster.com/aOMCoHKW_HMoTk4WU95W1GPFzBc=/300x300/v2/https://flxt.tmsimg.com/assets/p10883795_e_h9_aa.jpg" style="width:50%" height="170">
        
      </div>
    <!-- End photo grid -->
    </div>
  <!-- End Portfolio Section -->
  </div>

  <!-- Contact Section -->
  <div class="w3-padding-64 w3-content w3-text-grey" id="contact">
    <h2 class="w3-text-light-grey">Contact Me</h2>
    <hr style="width:200px" class="w3-opacity">

    <div class="w3-section">
      <p><i class="fa fa-map-marker fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Manila City,Philippines </p>
      <p><i class="fa fa-phone fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Phone: +63 9306337902</p>
      <p><i class="fa fa-envelope fa-fw w3-text-white w3-xxlarge w3-margin-right"> </i> Email: tom@gmail.com</p>
    </div><br>
    <p>Let's get in touch. Send me a message:</p>

    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Email" required name="Email"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Subject" required name="Subject"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Message" required name="Message"></p>
      <p>
        <button class="w3-button w3-light-grey w3-padding-large" type="submit">
          <i class="fa fa-paper-plane"></i> SEND MESSAGE
        </button>
      </p>
    </form>
  <!-- End Contact Section -->
  </div>
  
    <!-- Footer -->
  <footer class="w3-content w3-padding-64 w3-text-grey w3-xlarge">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
    <p class="w3-medium">Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank" class="w3-hover-text-green">w3.css</a></p>
  <!-- End footer -->
  </footer>

<!-- END PAGE CONTENT -->
</div>

</body>
</html>