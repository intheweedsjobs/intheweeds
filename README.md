# InTheWeeds

Service Industry Job Board for Austin TX - https://jonathanmatthey.github.io/


## Instructions KC

#### how to ADD a job

Jobs come in as pull requests in github

1. login to github
2. visit https://github.com/JonathanMatthey/intheweeds/pulls
3. click on any open PRs
4. review the details, if you approve, click the green button - MERGE PULL REQUEST
5. click the grey DELETE BRANCH button
6. the job is live !
7. if you don't want the job posted, click the grey button CLOSE PULL REQUEST, then also DELETE BRANCH

#### how to REMOVE a job

1. login to github
2. visit https://github.com/JonathanMatthey/intheweeds
3. click on the jobs folder
4. click on the job you want to delete
5. on the top right you'll see a little trash icon - click that
6. click the green button at the bottom of the page that reads COMMIT CHANGES
7. the job is gone !

#### how to update individual pages, like About and Events

1. login to github
2. visit https://github.com/JonathanMatthey/intheweeds
3. click on the events.html file
4. click the pencil icon on the top right, Edit
5. you're now editing html, find the whole <div> tag that has "row" as a classname, select the opening and closing tag, something like this:
  ```
  <div class="row event-row">
    <div class="col-md-2">
      <strong>20 March 2017</strong>
    </div>
    <div class="col-md-10">
    2nd Annual Rejuvenate and Rage (Post SXSW Service Industry Appreciation Party) @ Vulcan Gas Company 5pm to close <a href="https://www.facebook.com/events/141783913007019/">https://www.facebook.com/events/141783913007019/</a>
    </div>
  </div>
  ```

6. Copy all that text below it, you've created a second row in the events page.
7. change the date and event description
8. click the green button COMMIT CHANGES
9. visit the live page at http://www.intheweedsjobs.com/events and see if you're happy with the changes, if not, repeat


