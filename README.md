# Java EE 7 Samples #

# Install Tomcat #

### Get It

For every major Tomcat version there is one download page containing
links to the latest binary and source code downloads, but also
links for browsing the download directories and archives:
- [Tomcat 9](https://tomcat.apache.org/download-90.cgi)
- [Tomcat 8](https://tomcat.apache.org/download-80.cgi)
- [Tomcat 7](https://tomcat.apache.org/download-70.cgi)

To facilitate choosing the right major Tomcat version one, we have provided a
[version overview page](https://tomcat.apache.org/whichversion.html).

### Documentation

The documentation available as of the date of this release is
included in the docs webapp which ships with tomcat. You can access that webapp
by starting tomcat and visiting http://localhost:8080/docs/ in your browser.
The most up-to-date documentation for each version can be found at:
- [Tomcat 9](https://tomcat.apache.org/tomcat-9.0-doc/)
- [Tomcat 8](https://tomcat.apache.org/tomcat-8.5-doc/)
- [Tomcat 7](https://tomcat.apache.org/tomcat-7.0-doc/)


# Java EE tutorial examples

##檔案結構

src/ -- 包含Java一般的Class和Servlet
WebContent/ -- JSP放在這
WebContent/WEB-INF/lib -- 外部jar放這


## Build the examples

BmiA.java -- 單純用Servlet實現Bmi

BmiB.java -- 使用Servlet傳參數給Jsp顯示Bmi

HelloWorld.java -- 使用單一JSP實現Bmi
