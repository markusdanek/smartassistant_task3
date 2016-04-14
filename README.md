# SmartAssistant - Web Developer Interview Task

##Task 3 – Angular JS
Your task is to finish a simple AngularJS html page – angularJs.html. The page should display an advisor dummy data registered which is registered $scope in "advisor" variable. Please note that we are not expecting from you any AngularJS experience. Don’t worry if you don’t know AngularJS as you should be able to find all needed information (Google is your friend) and implement as much as you can.

**Requirements:**

* implement advisorPage directive (line 104). Directive should represent / display a single advisor page element (all attributes should be displayed) (pages are stored in advisor.pages)
* a html directive template should be placed inside advisorPage.template script (line: 124)
* the directive page html element should fill following contract (you can add other elements, display more
properties or attributes):

```
<ANY class="smrt42-page">
  <ANY class=”smrt42-page-text”>
    <!-- display page text here -->
  </ANY>
  <ANY class="smrt42-page-number”>
    <!-- page num here -->
  </ANY>
  <!-- all page questions should be displayed here -->
</ANY>
```
```
<!—single question contract -->
<ANY class="smrt42-question">
  <ANY class="smrt42-question-text">
    <!-- display question text here -->
  </ANY>
  <ANY class="smrt42-question-type">
    <!-- display question type here -->
  </ANY>
</ANY>
```

* pages with the page number > 3 should get an extra text element "bigger than 3" (page number is represented by pageNum attribute)
* if the question is mandatory (question.mandatory = true) add smrt42-mandatory-question CSS class on the question element
* implement and apply simple “angularJsExerciseFilter” filter (line: 98) which displays only pages with even numbers (pages are stored in advisor.pages collection, a page number is represented by pageNum attribute).
* for the first and the last page add additional CSS classes - respectively smrt42-first-page, smrt42-last-page
* CSS styling is not necessary
