# Saliha Kıvanç
  <!-- <h1>Heading level 1</h1>  -->  
  <!--<button type="button">Click Me! </button> -->  

root = Tk()      
canvas = Canvas(root, width = 300, height = 300)      
canvas.pack()      
img = PhotoImage(file="ball.ppm")      
canvas.create_image(20,20, anchor=NW, image=img)      
mainloop()   

<head>
<style>
.button1 {
  border: none;
  color: white;
  padding: 16px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
}
  

.button2 {background-color: #2E86C1;} /* mavii */
.button3 {background-color: #008CBA;} /* Blue */
</style>
</head>
<body>

<button class="button button1">CV</button>
<button class="button button2">ABOUT ME</button>

</body>

