# 1. create repo on GitHub first (via web) OR if you have GitHub CLI (gh):
gh repo create amosamue --public --description "Samuel Amoh — Frontend dev & accounting professional" --confirm

# 2. clone repo
git clone https://github.com/amosamue/amosamue.git
cd amosamue

# 3. create README.md (paste content into README.md)
cat > README.md <<'README'
# 👋 Hi, I'm Samuel Amoh

**Accounting Professional Turned Front-End Developer**  
Currently growing through the **ALX Software Engineering Program**

---

## About Me

I bring a unique blend of accounting expertise and software engineering skills. With a strong background in financial reporting, budgeting, and compliance, I’ve transitioned into the tech world to build user-focused web apps and efficient tools that solve business problems.

---

## Tech Stack

- **Languages:** HTML, CSS, JavaScript, Python  
- **Frameworks / Libraries:** React, TailwindCSS  
- **Tools & Practices:** Git, GitHub, Bash, Agile, Version Control

---

## Featured Projects

**airbnb-clone-project**  
A replication of Airbnb’s UI focused on responsive layouts and reusable React components.  
🔗 https://github.com/amosamue/airbnb-clone-project

*(More projects coming soon — building and refining daily!)*

---

## GitHub Stats

![Samuel's GitHub stats](https://github-readme-stats.vercel.app/api?username=amosamue&show_icons=true&theme=radical)

---

## Contact

- **LinkedIn:** https://www.linkedin.com/in/samuel-amoh-15620a190  
- **Email:** samuelamoh130@gmail.com

✨ I combine finance insight with software development to build practical solutions.
README

# 4. commit & push
git add README.md
git commit -m "chore: add profile README"
git push origin main
