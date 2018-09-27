**CMSI 370** Interaction Design, Fall 2018

# Assignment 1115

Once you have your front end sufficiently built out, it’s time to make it load up some real data, do real searches, save real information, etc. Strictly speaking, this part isn’t really interaction design nor implementation, but we want to do it so that your application has some genuine utility. Furthermore, if you do take on front end work in the future, you are likely to write code at this level anyway, even if it resides just below the user interface.

## Background Reading
For this assignment, you will most likely use the reference documentation of your chosen web service API. To review the big picture, you can refer back to [this Prezi](https://prezi.com/nuggtz-wcyd1/modern-web-sites-annotated/) along with the class screengrab recording that talks through this big picture.

## Best Practices and Automated Feedback
Because you are using the same repository for this assignment, you should be good to go with automated feedback. If not, then _what’s taking you so long?_

## For Submission: API Integration
Replace the API stubs and mocks in your front end with actual requests to your chosen web service API. If you maintained the recommended design for this layer in [Assignment 1025](./front-end-development.md), then this part should be a no-brainer: once finished, your front end will “just work” and immediately shift to reading and writing real information to/from your chosen web service API.

The starter code for the three technology stacks all contain an extra “real API” file that genuinely implements one web service API call for you. Pattern your full API implementation after that code.

Once this step is finished, you should have a complete application, with a user interface of your design and implementation communicating with a real-world web service.

### How to Turn it In
Edit your front end code “in place” (i.e., keep on working on the code that you submitted for [Assignment 1025](./front-end-development.md)) and continue to commit and push it as needed. If you need to revisit first principles, you can refer to the original starter code in the repository (aren’t you glad that you copied these files in the beginning, rather than going straight to editing them?).

Thus, your submission is simply a continuation of the work that you started with the front end. Evaluating your work will proceed as before, based on the files at the top level of the repository.

## Specific Point Allocations
Programming assignments are scored according to outcomes _3a_, _3b_, and _4a_ to _4f_ in the [syllabus](http://dondi.lmu.build/fall2018/cmsi370/cmsi370-fall2018-syllabus.pdf). For this particular assignment, graded categories are as follows:

| Category | Points | Outcomes |
| -------- | -----: | -------- |
| API Calls (evenly divided among the implemented 3 or more calls)  | 60 | _3a_, _3b_, _4a_, _4b_, _4d_ |
| Test Suite and Coverage | 20 | _4a_ |
| Linting | deduction only | _4c_ |
| Version Control | deduction only | _4e_ |
| Punctuality | deduction only | _4f_ |
| **Total** | **80** |

The last three graded categories are “deduction only,” meaning that you will only get points taken off if there are significant issues with those categories. Such issues include but are not limited to: lingering linting errors as of the final commit (_4c_), insufficiently granular or unmessaged commits (_4e_), and late commits (_4f_).
