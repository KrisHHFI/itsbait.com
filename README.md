# ItsBait.com

<img src="PromoImage.png" width="1000"/>

<sub><i>Project Screenshot (25/05/2025)</i></sub>

<br/>

I am currently working on an AI image detector site called [ItsBait.com](https://itsbait.com/). I began the project on the 03/03/2025. Please note that this repository may not be up to date. To get the latest news on the project, checkout the website or the YouTube channel.

<br/>

## Social Links
[YouTube](https://www.youtube.com/@its_bait)<br/>
[Patreon](https://www.patreon.com/c/Its_BAIT)<br/>

<br/>

## Design

### Logo (Photoshop)

<details><summary></summary>
  
<br/>

The project logo was designed in Photoshop. I use Photoshop because it is a familiar tool due to my background in photography. I work in a non-destructive way, taking a layered approach.  I also created my own font to avoid potential future copyright issues.

<img src="project-logo-photoshop.png" alt="Project logo in Photoshop" width="600"/>

<sub><i>Project logo in Photoshop</i></sub>

<br/>

</details>

### Project Design & Layout (Figma)

<details><summary></summary>
  
<br/>

[Figma Project](https://www.figma.com/design/syI8LP7xcRRHivfSHIyY49/It-s-Bait?node-id=0-1&t=ol3NF4RAXrJtyyDr-1)

<br/>

<img src="figma-mobile-layout.png" alt="Project mobile layout in Figma" width="600"/>

<sub><i>Project mobile layout in Figma</i></sub>

<br/>

</details>

<br/>

## Testing

### Functional Tests (Robot Framework)

<details><summary></summary>
  
<br/>
  
I am using Robot Framework for functional tests. With Robot Framework I can run tests which simulate user behavior. With this software, I can watch live as the test unfolds on my site. My current tests upload images and then ensure that specific text is found in the report. The tests themselves are in another one of my [repositories](https://github.com/KrisHHFI/Its-Bait-Robot-Tests).

<br/>

Currently, I have a generic function which goes to the site, presses the upload button and then uploads an image (according to the passed file location). Then, the test checks for image specific text in the Bait report.

<img src="robot-framework-test-result.png" alt="Results from one of the .robot test files." width="600"/>

<sub><i>Screenshot of one of the .robot test files.</i></sub>

<br/>

</details>

### Unit Tests (Vitest)

<details><summary></summary>
  
<br/>
  
In the project I am using Vitest for unit testing. The React project was built using Vite, so Vitest (which is a Vite package) seemed like the obvious choice. I have established a series of tests for the project. My tests ensure that all the different pages and their content render and that the website navigation works correctly.
    
<img src="vitest-test-results.png" alt="Vitest files and test results" width="600"/>

<sub><i>Screenshot of the test files and their results</i></sub>

<br/><br/>

With Vitest you can run the tests continuously in the background. Whenever you make a change to a file the tests will run again. If the file you are working with is implicated in certain tests, then only those specific tests will run. Otherwise, all the tests will run. This means that you can work on the project and not worry about breaking things.
  
<img src="specific-vitest-test-results.png" alt="Image showing specific test files being ran" width="600"/>

<sub><i>Screenshot showing only relevant test files being ran</i></sub>

<br/><br/>

<img src="individual-vitest-test-results.png" alt="Image showing specific test results" width="600"/>

<sub><i>Screenshot showing the results of a single test</i></sub>

</details>
