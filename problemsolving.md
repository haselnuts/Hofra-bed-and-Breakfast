# All Jinja issues will be listed here

## jinja2.exceptions.TemplateNotFound: index.html
 - code
    @app.route("/")
    def index():
        return render_template("index.html")
- Code was correct but filepath for templates was not as planned
 - Filepath before: /workspace/Hofra-bed-and-Breakfast/static/templates
 - Filepath after: /workspace/Hofra-bed-and-Breakfast/templates


# All Werkzeug issues will be listed here

## werkzeug.routing.BuildError: Could not build url for endpoint 'vara-rum'. Did you mean 'varaRum' instead
 - Code 
    @app.route("/vara-rum")
    def varaRum():
        return render_template("vara-rum.html")
 - Code changed to 
    @app.route("/varaRum")
    def varaRum():
        return render_template("vara-rum.html")

## werkzeug.routing.BuildError: Could not build url for endpoint 'dellenbygden'. Did you mean 'dellenbygen' instead?
 - Code 
    @app.route("/dellenbygden")
    def dellenbygen():
        return render_template("dellenbygden.html")
- Found missing "d" in def dellenbygen(), corrected code to 
    @app.route("/dellenbygden")
    def dellenbygden():
        return render_template("dellenbygden.html")


# All related CSS issues will be listed here

# All related HTML issues will be listed here

## Website does not contain any CSS
 - Assuming that filepath from base.html to style.css is incorrect
 - Code before: link rel="stylesheet" href="assets/css/stylesheet.css" type="text/css"
 - Code after: link rel="stylesheet" href="{{ url_for("static", filename:"css/style.css") }}" type="text/css"
 - *CSS still not working*
 - Checked code and found colon instead of equal after filename
 - Code corrected to: link rel="stylesheet" href="{{ url_for("static", filename="css/style.css") }}" type="text/css"


