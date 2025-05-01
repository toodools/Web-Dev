# Web-Dev
git checkout -b Java

echo "public class HelloWorld { public static void main(String[] args) { System.out.println(\"Hello Java\"); } }" > HelloWorld.java
git add HelloWorld.java
git commit -m "v1: Initial Java HelloWorld script"
 
git checkout main
git checkout -b JavaScript
 
echo "console.log('Hello JavaScript');" > hello.js
git add hello.js
git commit -m "v1: Initial JavaScript HelloWorld script"
