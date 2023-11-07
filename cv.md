# Vitaliy Tarassov
🙋‍♂️ Hello and welcome!
<div align="center">
  If you don’t walk today, you’ll have to run tomorrow 🎯  
</div>
<br>
<div align="center">
  <picture>
    <source srcset="https://user-images.githubusercontent.com/74038190/264141683-8aa99f6c-267d-4977-9cd3-1a4c11675863.gif"  width="298" height="212" media="(max-width: 576px)">
    <img src="https://user-images.githubusercontent.com/74038190/264141683-8aa99f6c-267d-4977-9cd3-1a4c11675863.gif" width="498" height="312"> 
  </picture> 
  
  [![codewars](https://www.codewars.com/users/vtarasso/badges/small?theme=light)](https://www.codewars.com/users/vtarasso) 
</div>

## 😉 A few words about myself

* My name is Vitaliy Tarassov.   
* I'm a future Frontend-developer.   
* 🖥 Experienced in cross-browser, adaptive layout of websites. 
* 📚 In the process of learning and developing my knowledge. Moreover, I have big plans for that! 🙂
  
## :hammer_and_wrench: Skills:

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original-wordmark.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/go/go-original-wordmark.svg" title="Golang" alt="Golang" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/figma/figma-original.svg" title="Figma" alt="Figma" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/photoshop/photoshop-line.svg" title="Photoshop" alt="Photoshop" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" **alt="Git" width="40" height="40"/>
</div>

## Contacts


##  💻 Experience
### Links to my training projects
* [Groupie-tracker](https://groupie-tracker-553n.onrender.com) - A training project made in Golang. Display information from deleted json files on the page. Weak optimisation, you will have to wait for downloading the deployed version. [Video link](https://www.youtube.com/watch?v=8p2bzAx-5JM)
* [Forum](https://forum-b1fn.onrender.com) - A training project made in Golang. The name speaks for itself. A site-forum, where you can register, leave posts, like, dislike. Weak optimisation, you will have to wait for the download of the deployed version. [Video link](https://www.youtube.com/watch?v=HLdnLD4Q1GM)
* [Ascii-Art-Generator](https://ascii-art-r29i.onrender.com) - A training project made in the Golang language. The name speaks for itself. 
The site is an analogue of the ascii art generator. Weak optimisation, you will have to wait for the download of the deployed version. [Video link](https://www.youtube.com/watch?v=xpDpq2EZQRQ)
* [Euclid](https://vtarasso.github.io/euclid-v2.0)- Adaptive Landing Page
* [Cyberpunk-promo](https://vtarasso.github.io/cyberpunk) - Adaptive Landing Page

## 📟 Examples of my code

```
func ErrorHandler(w http.ResponseWriter, code int) {
	tmpl, err := template.ParseFiles(ErrorPage, TemplatePage)
	if err != nil {
		http.Error(w, "Internal Server Error", 500)
		return
	}
	w.WriteHeader(code)
	errInf := Err{code, http.StatusText(code)}
	err = tmpl.Execute(w, errInf)
	if err != nil {
		http.Error(w, "Internal Server Error", 500)
		return
	}
}
```
## 🔖  Courses
👨‍🎓 [Alem01](https://alem.school/) educational school [alumni](https://alem.school/certificates/alumni/vtarasso).   

## Languages
* Russian - Native Speaker
* English - A2
* Kazakh - A2 
