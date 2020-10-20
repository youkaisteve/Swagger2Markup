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

# successful url
http://172.16.0.131:3010/api-docs/html/${swagger.project.name}.html
http://172.16.0.131:3010/api-docs/pdf/${swagger.project.name}.pdf
```
