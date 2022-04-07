# Demetre Kurdadze

## My Contact Info

---

- Adress: Tbilisi st.18, rustavi, Georgia
- phone: +995 598-93-56-29
- E-mail: Demetrekurdadze@gmail.com
- LinkedIn: https://www.linkedin.com/in/demetre-kurdadze-b62980198/
- GitHub:  <a href="https://github.com/Demetrusa">Demetrusa</a>
- Facebook: <https://www.facebook.com/Qurdadzeee/>

---

## Summary

My name is Demetre Kurdadze, I live in Georgia, Rustavi, 27 years old. While studying at university, I became interested in learning web programming, and I realized that this was my favorite profession. I started studying programming courses. I was very attracted to JavaScript. I am eager and can work in a group. Can easily work with Git.Also can work with responsive design.

## Skills

---

- Html5
- CSS
- Bootstrap
- Responsive Design
- Javascript
- React Basic
- Git Version Control
- Figma(for web development)
- Editors: VSCode, Sublime.

---

### Code Example

```javascript
    function Skill () {
    const [skill, setSkill] = useState([]);
    const [selected, setSelected] = useState('');
     useEffect(()=>{
        fetch('https://bootcamp-2022.devtest.ge/api/skills')
        .then( (response) => response.json())
        .then(function(data){
                setSkill(data)
            }).catch(function(){
                alert("error");
            });
    },[])
      const addSkill = (e) => { 
      const selectedSkill = e.target.value;
      setSelected(selectedSkill);
    }
    return (
        <div className="skillForm">
                <select name="custom-select" id="skillChange" placeholder="Skills" onChange={addSkill}>
                    {skill? skill.map((item, index ) => {
                        return (
                            <option key={item.id} value={item.title}>{item.title}</option>
                        )
                    }) : null
                  }
                </select>
        </div>
    )
```

### Education
---
- Geolab Front end courses(2021)-Web Programming Front End (HTML, CSS) 
  <a href="https://drive.google.com/file/d/1k-mkrjLDl_8BUTUPaJRK-cYx_LF1kX4h/view">Sertificate</a>
- Geolab Javascript Course(2021-2022) -JavaScript / React (still on it)
- School of Business, Bachelor's Programme (Major)Business  Administration
  * (Management, Banking  and  Finance, Tourism, Sport Management) (Major Programmes)
  * Bachelor's Programme (Minor)- (Free Component(Structured Programming, Web programing)
  * Direction: Banking and Finance! (2013-2017)
- Ilia State University(Master)
  * Master's Programme - Business  Administration (Management, Banking  and  Finance, Tourism  Management)
  * Direction: Management (2018-2021)

---
### Experience 
* Mini projects for apliactions
---