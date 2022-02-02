# 0x09. Implement a design from scratch


In this project, you will implement from scratch, without any library, a web page. 
You will use all HTML/CSS/Accessibility/Responsive design knowledges that you learned previously. 
You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have a fully functional web page that looks the same as the designer file.
Here the final result:
<img src="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/60df485eb772ecbad54a.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20210823%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20210823T154022Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=fffcb62407b2bc0fa751b7449b59ca71111e9998fb6802c80d9e2242809067e8" alt="" style="">
This webpage has been designed by Nicolas Philippot, UI/UX designer.
You can find final screens [here](https://intranet-projects-files.s3.amazonaws.com/holbertonschool-webstack/622/Archive.zip)

### Requirements
  + you are not allowed to import external CSS framework (like Bootstrap)
  + you are not to use Javascript


## 0. Read and be familiar with Figma
Create an account in <a href="/rltoken/eumOUW-eMS4X9ZDZg9KPLg" title="Figma" target="_blank">Figma</a> and open this <a href="/rltoken/2ED3P1a2wnbQqRLi8aXJKw" title="project" target="_blank">project</a> and “Duplicate to your Drafts” to have access to all design details.

Create an account in [Figma](https://intranet.hbtn.io/rltoken/eumOUW-eMS4X9ZDZg9KPLg) and open this [project](https://intranet.hbtn.io/rltoken/2ED3P1a2wnbQqRLi8aXJKw) and “Duplicate to your Drafts” to have access to all design details.

If you can’t access to it, please find here the [Figma file](https://intranet.hbtn.io/rltoken/NxsDNicWs5KSlsR94kt52A)

<img src="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20210823%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20210823T154022Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=7b3b73111dc7a4887362099965ccb17efac799e85f2c26c3a2d43c298a17e291" alt="" style="">

Important notes with Figma:
  + if your computer doesn’t have missing fonts, you can find them here: [source-sans-pro](https://intranet.hbtn.io/rltoken/wltHny-KZP3B8JFRvpmVjA) and [Spin-Cycle-OT](https://intranet.hbtn.io/rltoken/Qb96K4nTPQJO1paP_OBELw)
  + some values are in float - feel free to round them

For this task, please write an amazing `README.md`

**Interactions note:**
  + the web page must switch to the mobile version when the screen width is 480px or less
  + links hover/active: `#FF6565`
  + button hover/active: `opacity: 0.9`
  + max width of the content: 1000px centered in the page


## 1. Header
Building a web page the right way, is not easy - expect if you put in place strong foundations:

Building a web page the right way, is not easy - expect if you put in place strong foundations:
  + reset CSS styling
  + use variables
  + simple/“as generic as you can” CSS selectors
  + avoid using super specific CSS selectors as much as possible
  + simple HTML structure - `div` containers are your friend!

Last advice: Personally, I always start to build a web page from outside to inside and from top to bottom. 
But you can try to other way - it’s fine - but you should structure the way that you will implement a component and not get lost with HTML tags.

Now, your turn!

For this first task: **create the header/hero piece**

Here an archive of all assets needed: [images_0x09.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/d1597894d79386c83b9b.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20210823%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20210823T154022Z&amp;X-Amz-Expires=345600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=52c998e3d01e6462b580e530ec54df81d9c59eb4eaf749231fca332fce01006f)

**Desktop:**
![Desktop](https://github.com/CSant04y/holberton-headphones/blob/master/01_headphones_desktop@2x.png?raw=true)

**Mobile:**

<img src="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/75a582f98640445a2dbf.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20210823%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20210823T154022Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=4cdeb905feff17d5d1fcc42728668cc07d7ad624b8e99fc0a1cea6e65163e73f" alt="" style="">


## 2. "What we do..." section
Copy files from the previous task.

Copy files from the previous task.

For this second task: **create the “What we do…” section**

In this section, you will need custom font icons. Here the archive of it: [holberton_school-icon.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/7159d988278de54d859d.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20210823%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20210823T154022Z&amp;X-Amz-Expires=345600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=eb6003fe6d799948d2a32c49f8aed0192e027483ae254a7fbf07308491dbd38a)

Inside you will find demo page of how to use it.

**Important:** try to build as generic as you can… you will probably need some components in next section.


## 3. "Our results" section
Copy files from the previous task.

Copy files from the previous task.

For this third task: **create the “Our results” section**

Now you can reuse components form the previous task!


## 4. Contact us
Copy files from the previous task.

Copy files from the previous task.

A good landing page has always a contact form.

You are free to add any animations and/or constraints on fields.


## 5. Footer
Copy files from the previous task.

Copy files from the previous task.

Last piece of the page… the Footer!

When you are done, here the result:

**Desktop:**
![Desktop](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/3b5a9f7948a58d58bd43.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20210823%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20210823T154022Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=f2bb0c9b7b9530ef93549dc88dce40faa5ac0d6afc325da0839f68ab09a6cd0c)
<img src="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/3b5a9f7948a58d58bd43.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20210823%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20210823T154022Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=f2bb0c9b7b9530ef93549dc88dce40faa5ac0d6afc325da0839f68ab09a6cd0c" alt="" style="">

**Mobile:**

<img src="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/83d6311e87d4775ca4b3.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20210823%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20210823T154022Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=89fbc7dbd707ef2972590885831b1821a1f81ef9b4fdcb37b4dac6a02191f919" alt="" style="">

And you are done! 

**Good job!**

## About me

### **Carlos Esquivel**
Carlos Esquivel is originally from Tulsa. After taking a gap year and working in sales, he decided to make a switch into the technology industry to obtain skills in software engineering. As the pandemic hit, Holberton school provided an opportunity to learn and grow in a remote working environment.

As a software engineering student, Carlos enjoys the creative aspects of problem solving such as how collaboration can foster the transfer of knowledge.

* 📖 [Medium](https://1831-9922.medium.com/)
* :bird:[Twitter](https://twitter.com/esquivelcarlo12)

* :robot: [GitHub](https://github.com/CSant04y)

* :briefcase: [LinkedIn](https://www.linkedin.com/in/carlos-esquivel-515768186/)
