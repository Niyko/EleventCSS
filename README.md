## Components
### Button
`````Html
<button class="el-btn uk-margin-top">Learn more</button>
<button class="el-btn el-btn-small el-btn-primary uk-margin-top">Learn more</button>
<button class="el-btn el-btn-small el-btn-outline uk-margin-top">Learn more</button>
`````

### Link
`````Html
<a class="el-link">Edit</a>
<a class="el-link el-link-primary">Delete</a>
`````

### Nav bar
`````Html
<div class="el-nav uk-flex uk-flex-middle">
    <div class="uk-container uk-width-1-1">
      <div uk-grid class="uk-grid-small">
        <div class="uk-flex uk-flex-middle">
          <a class="el-btn-round-icon el-btn-round-icon-primary el-icon">menu</a>
        </div>
        <div class="uk-flex uk-flex-middle">
          <p class="el-nav-title">Elevent</p>
        </div>
        <div class="uk-width-expand"></div>
        <div class="uk-flex uk-flex-middle">
          <a class="el-nav-link">Browse components</a>
        </div>
        <div class="uk-flex uk-flex-middle">
          <button class="el-btn el-btn-small el-btn-primary">Learn more</button>
        </div>
      </div>
    </div>
  </div>
`````

### Content
`````Html
<h2 class="el-hg-2 uk-margin-remove uk-text-bolder">Lorem ipsum dolor sit, amet consectetur adipisicing elit</h2>
<h2 class="el-hg-2 uk-margin-remove uk-text-bolder el-text-primary">Lorem ipsum dolor sit, amet consectetur adipisicing elit</h2>
<p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Illum provident reiciendis atque sed id modi esse, doloribus aliquam iure deserunt qui placeat soluta hic porro molestiae quam similique iste. Libero?</p>
`````

### Table
`````Html
<table class="el-table uk-width-1-1 uk-margin-top">
    <thead>
        <tr>
            <th>Table Heading</th>
            <th>Table Heading</th>
            <th>Table Heading</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Table Data <span class="el-badge">New one</span></td>
            <td>Table Data</td>
            <td>
        <a class="el-btn-round-icon el-btn-round-icon-primary el-icon">delete</a>
      </td>
        </tr>
        <tr>
            <td>Table Data</td>
            <td>Table Data</td>
            <td>
        <a class="el-link el-link-primary">Edit</a>
      </td>
        </tr>
        <tr>
            <td>Table Data</td>
            <td>Table Data</td>
            <td>Table Data</td>
        </tr>
    </tbody>
</table>
`````

### Form
`````Html
<form>
  <div>
    <label class="el-label">Your name <span class="el-required"></span></label>
    <input class="el-input uk-width-1-1" placeholder="Eg: Dora" type="text">
  </div>
  <div class="uk-margin-top">
    <select class="el-input el-select uk-width-1-1" autocomplete="off">
      <option selected disabled>Select one</option>
      <option>Option</option>
    </select>
  </div>
  <div>
    <input class="el-checkbox" name="hello" type="checkbox">
  </div>
  <div>
    <input class="el-radio" name="name" type="radio">
  </div>
</form>
`````

### Card
`````Html
<div class="el-card uk-padding"></div>
`````

### Modal
`````Html
<div id="modal-example" uk-modal>
  <div class="uk-height-1-1">
    <div class="uk-height-1-1 uk-flex uk-flex-middle">
      <div class="el-modal uk-modal-dialog uk-modal-body">
        <div uk-grid class="uk-grid-small">
          <div class="uk-width-auto">
            <span class="el-icon el-icon-box">priority_high</span>
          </div>
          <div class="uk-width-expand">
            <h4 class="el-hg-4 uk-text-bold uk-margin-remove">Deactivate account</h4>
            <p class="uk-margin-small-top">Are you sure you want to deactivate your account? All of your data will be permanently removed. This action cannot be undone. </p>
          </div>
        </div>
        <p class="uk-text-right">
          <button class="el-btn el-btn-small el-btn-outline uk-margin-top">Close</button>
          <button class="el-btn el-btn-small el-btn-primary uk-margin-top">Deactivate</button>
        </p>
      </div>
    </div>
  </div>
</div>
`````

### Badge
`````Html
<span class="el-badge">New one</span>
`````
