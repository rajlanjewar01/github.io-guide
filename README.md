<div align="center">
  <a href="#">
    <img src="images/maxresdefault.jpg" alt="Logo">
  </a>

  <h3 align="center">A Guide to host your Static website with Github Pages</h3>

  <p align="center">
    <a href="https://youtu.be/7BE2FHu3l9o"><strong>Watch step by step guide video »</strong></a>
  </p>
</div>

## Step By step Guides:


<img src="images/0.png" alt="img">
1) Visit to Github.com and Create new repository by clicking "New"


<img src="images/1.png" alt="img">
2) step 2: provide repository name (in our case *my-demo-website),   *important Choose "Public" and click Create repository
	(reason of choosing public is that in Basic/Free plan Github only allow Github pages repository to be public)
  
<img src="images/2.png" alt="img">
3) step 3: Copy the highlighted link, Create any folder in Desktop -> Open it -> Right click inside folder and open Git Base Here 
	[if you are not have git base installed visit to following link https://git-scm.com/downloads  download and install it].
  
<img src="images/3.png" alt="img">  
4) step 4: Goto github.com you can see repository that we just created copy full .git link by clicking copy icon.  In Git Base terminal 
	write following commands <b>git clone https://github.com/rajperficient01/my-demo-website.git</b> and hit enter
	Now inside your folder you can see one folder is being created  -> close Git Base now -> open newly created folder(in our case my-demo-website folder) and now open 
	Git Base here by right clicking here.
  
<img src="images/4.png" alt="img">
<img src="images/5.png" alt="img">
5) Next step is to paste your source code here : copy and paste your code all files -> In git base type following commands
	git status
	git add .
	git commit -m "initial commit"
	git push
  
<img src="images/6.png" alt="img">
6) And now if you visit to you github you can see your files added (refresh the browser)

7)Open the setting tab

<img src="images/7.png" alt="img">
8) scrool down -> in left menu clicke on "Pages"

<img src="images/8.png" alt="img">
9) Now inside Source dropdown choose "Main" (main in branch name-your main/origin branch) -> next dropdown is automatically selected leave it default
and now click on "Save"

<img src="images/9.png" alt="img">
<img src="images/10.png" alt="img">
10) the page is automatically refreshing and after that you will get link to your live website
--> And now share this link with your friends https://rajperficient01.github.io/my-demo-website/ 

	

























1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] Add Changelog
- [x] Add back to top links
- [ ] Add Additional Templates w/ Examples
- [ ] Add "components" document to easily copy & paste sections of the readme
- [ ] Multi-language Support
    - [ ] Chinese
    - [ ] Spanish

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

