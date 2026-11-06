<a href="/movies">Back</a>
<h1>Add a Movie</h1>

<form method="POST">
  <div class="mb-3">
    <label for="title" class="form-label">Name</label>
    <input id="title" name="title" type="text" class="form-control" required />
  </div>

  <div class="mb-3">
    <label for="year" class="form-label">Year</label>
    <input id="year" name="year" type="number" class="form-control" required />
  </div>

  <div class="mb-3">
    <label for="length" class="form-label">Length</label>
    <input id="length" name="length" type="text" class="form-control" placeholder="z. B. 114 Minuten" required />
  </div>

  <button type="submit" class="btn btn-primary">Add Movie</button>
</form>