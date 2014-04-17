# Github Reviewboard extension
---
An extension for Reviewboard rbt command to preview and apply github pull requests. The inital focus of this is to help Apache projects using Reviewboard and allow them to also manage Github pull requests using the same tooling.


### Usage
---
To get started install rbt and rbt-github

	easy_install rbt rbt-github
	
Configure your .reviewboardrc

	GITHUB_OWNER = "apache"
	GITHUB_REPO = ""
	
To preview a given pull request patch

	rbt github -p 5
	
To apply and commit the patch

	rbt github -c 5
	

### License
---
Except as otherwise noted this software is licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
