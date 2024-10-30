
<div class="container">
    <h1>🔐 Random Password Generator</h1>

  <div class="preview">
        <img src="https://i.ibb.co/LPZGBSb/image-1.png" alt="Password Generator Preview">
    </div>
    <p align="center"><strong>Generate secure, random passwords quickly and easily with this aesthetically pleasing web-based password generator. it’s perfect tool for keeping your accounts safe!</strong></p>

  <div class="section">
        <h2>✨ Features</h2>
        <ul>
            <li>Random Password Generation with uppercase, lowercase, numbers, and symbols.</li>
            <li>Copy to Clipboard for easy usage.</li>
            <li>User-Friendly Interface with an aesthetically pleasing background.</li>
        </ul>
    </div>

  <div class="section">
        <h2>🚀 Installation</h2>
        <p>1. Clone the Repository:</p>
        <div class="code">
            <code>
                git clone https://github.com/your-username/random-password-generator.git <br>
                cd random-password-generator
            </code>
        </div>
        <p>2. Open <code>index.html</code> in Your Browser.</p>
    </div>

  <div class="section">
        <h2>🛠️ Usage</h2>
        <ol>
            <li>Click <strong>Generate</strong> to create a new password.</li>
            <li>Press the <strong>Copy</strong> icon to copy the password to your clipboard.</li>
            <li>Repeat as needed to create secure passwords!</li>
        </ol>
    </div>

  <div class="section">
        <h2>💻 Technologies Used</h2>
        <ul>
            <li><strong>HTML</strong> for structuring the page</li>
            <li><strong>CSS</strong> for styling, with a clean and modern design</li>
            <li><strong>JavaScript</strong> for generating the password and handling the clipboard copy</li>
        </ul>
    </div>

  <div class="section">
        <h2>🔍 How It Works</h2>
        <p>This app generates a secure password using random characters from a set of uppercase letters, lowercase letters, numbers, and symbols. JavaScript’s <code>Math.random()</code> function ensures that each password generated is unique.</p>
        <div class="code">
            <code>
                function createPassword(){ <br>
                &nbsp;&nbsp;&nbsp;&nbsp;let password = ""; <br>
                &nbsp;&nbsp;&nbsp;&nbsp;password += upperCase[Math.floor(Math.random() * upperCase.length)]; <br>
                &nbsp;&nbsp;&nbsp;&nbsp;password += lowerCase[Math.floor(Math.random() * lowerCase.length)]; <br>
                &nbsp;&nbsp;&nbsp;&nbsp;password += number[Math.floor(Math.random() * number.length)]; <br>
                &nbsp;&nbsp;&nbsp;&nbsp;password += symbol[Math.floor(Math.random() * symbol.length)]; <br><br>
                &nbsp;&nbsp;&nbsp;&nbsp;while(password.length &lt; 12){ <br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;password += allCharc[Math.floor(Math.random() * allCharc.length)]; <br>
                &nbsp;&nbsp;&nbsp;&nbsp;} <br>
                &nbsp;&nbsp;&nbsp;&nbsp;passwordBox.value = password; <br>
                }
            </code>
        </div>
    </div>

  <div class="section">
        <h2>🤝 Contributing</h2>
        <ol>
            <li><strong>Fork</strong> the repository.</li>
            <li>Create a feature branch for your modifications.</li>
            <li>Submit a pull request for review.</li>
        </ol>
    </div>

  <footer>
        <p>Licensed under the MIT License</p>
        <p>Enjoy a simple, secure, and beautiful password generation experience!</p>
    </footer>
</div>
