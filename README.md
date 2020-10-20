# Swagger2Markup

This is a tool for generating api documents(html and pdf) via swagger2. 

# Usage

```bash
git clone https://github.com/youkaisteve/Swagger2Markup.git
cd Swagger2Markup
mvn compile

# You'll find the output files in ${project.basedir}/doc
```

# optional

```bash
mvn package -Dswagger.project.url=http://localhost:3001/ -Dswagger.project.name=ibuild-web
```
