# FI Labs Automator

This is an application that automates lab tests, outputs the results and cleans the cloned repository.

### How to use

To use it remotely visit https://fi-labs-automator.herokuapp.com/
or if you like, you can download it and install it on you machine by runing

```
git clone https://github.com/njmwasmoringa/fi-lab-test-automator
cd fi-lab-test-automator
npm install
npm start
```

<p>Welcome to <%= title %>
    </p>

    <h3>Lab Repository</h3>
    <p>Enter the lab repository link below</p>
    <form onsubmit="runtest(event)">
      <div class="row">
        <div class="col-9">
          <input type="url" name="repolink" class="form-control" id="repolink" placeholder="Repository Link: https://"
            required />
        </div>

        <div class="col-3">
          <button type="submit" class="btn btn-primary" id="submitButton">Submit Link</button>
        </div>
      </div>
      <div class="link">
        <h6>Link Submission</h6>
        <div class="wrapper"></div>
        <div class="wrapper"></div>
      </div>
      <div id="output"></div>
    </form>
