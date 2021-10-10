<h1>Sticky Notes</h1>
<h4>This is a notes web app with html, css bootstarp and javascript</h4>
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Notes App</title>
    <link rel="icon" type="image/png" href="notes.png"/>
    <link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
      integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T"
      crossorigin="anonymous"
    />
  </head>

  <body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <a class="navbar-brand" href="#">Sticky Notes</a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
       </form>
      </div>
    </nav>
<div class="container my-3">
      <h1>Welcome To Sticky Notes</h1>
      <div class="card border-dark mb-3">
        <div class="card-body">
          <h5 class="card-title">Add a note</h5>
          <div class="form-group">
            <textarea class="form-control" id="addTxt" rows="3"></textarea>
          </div>
          <button class="btn btn-primary" id="addBtn">Add Note</button>
        </div>
      </div>
      <hr />
      <h1>Your Notes</h1>
      <hr />
      <div id="notes" class="row container-fluid"></div>
    </div>
 </body>
</html>
