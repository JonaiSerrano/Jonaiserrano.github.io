<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Project</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header, footer {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: auto;
            padding: 1rem;
        }
        footer p {
            margin: 0;
        }
        img {
            max-width: 100%;
            height: auto;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        table, th, td {
            border: 1px solid #ddd;
        }
        th, td {
            padding: 0.5rem;
            text-align: left;
        }
        code {
            background-color: #f4f4f4;
            padding: 0.2rem 0.4rem;
            border-radius: 3px;
        }
        pre {
            background-color: #f4f4f4;
            padding: 1rem;
            border-radius: 3px;
            overflow-x: auto;
        }
        blockquote {
            border-left: 4px solid #ddd;
            padding-left: 1rem;
            margin: 1rem 0;
            color: #666;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Project</h1>
    </header>
    
    <div class="container">
        <p>Text can be <strong>bold</strong>, <em>italic</em>, <del>strikethrough</del> or <code>keyword</code>.</p>

        <p><a href="./another-page.html">Link to another page</a></p>

        <p>There should be whitespace between paragraphs.</p>
        
        <h1>Header 1</h1>
        <p>This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.</p>

        <h2>Header 2</h2>
        <blockquote>
            <p>This is a blockquote following a header.</p>
            <p>When something is important enough, you do it even if the odds are not in your favor.</p>
        </blockquote>

        <h3>Header 3</h3>
        <pre><code class="language-js">
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
        </code></pre>
        
        <pre><code class="language-ruby">
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
        </code></pre>

        <h4>Header 4</h4>
        <ul>
            <li>This is an unordered list following a header.</li>
            <li>This is an unordered list following a header.</li>
            <li>This is an unordered list following a header.</li>
        </ul>

        <h5>Header 5</h5>
        <ol>
            <li>This is an ordered list following a header.</li>
            <li>This is an ordered list following a header.</li>
            <li>This is an ordered list following a header.</li>
        </ol>

        <h6>Header 6</h6>
        <table>
            <thead>
                <tr>
                    <th>head1</th>
                    <th>head two</th>
                    <th>three</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>ok</td>
                    <td>good swedish fish</td>
                    <td>nice</td>
                </tr>
                <tr>
                    <td>out of stock</td>
                    <td>good and plenty</td>
                    <td>nice</td>
                </tr>
                <tr>
                    <td>ok</td>
                    <td>good <code>oreos</code></td>
                    <td>hmm</td>
                </tr>
                <tr>
                    <td>ok</td>
                    <td>good <code>zoute</code> drop</td>
                    <td>yumm</td>
                </tr>
            </tbody>
        </table>

        <h3>There's a horizontal rule below this.</h3>
        <hr>

        <h3>Here is an unordered list:</h3>
        <ul>
            <li>Item foo</li>
            <li>Item bar</li>
            <li>Item baz</li>
            <li>Item zip</li>
        </ul>

        <h3>And an ordered list:</h3>
        <ol>
            <li>Item one</li>
            <li>Item two</li>
            <li>Item three</li>
            <li>Item four</li>
        </ol>

        <h3>And a nested list:</h3>
        <ul>
            <li>level 1 item
                <ul>
                    <li>level 2 item</li>
                    <li>level 2 item
                        <ul>
                            <li>level 3 item</li>
                            <li>level 3 item</li>
                        </ul>
                    </li>
                </ul>
            </li>
            <li>level 1 item
                <ul>
                    <li>level 2 item</li>
                    <li>level 2 item</li>
                    <li>level 2 item</li>
                </ul>
            </li>
            <li>level 1 item
                <ul>
                    <li>level 2 item</li>
                    <li>level 2 item</li>
                </ul>
            </li>
        </ul>

        <h3>Small image</h3>
        <img src="https://github.githubassets.com/images/icons/emoji/octocat.png" alt="Octocat">

        <h3>Large image</h3>
        <img src="https://guides.github.com/activities/hello-world/branching.png" alt="Branching">

        <h3>Definition lists can be used with HTML syntax.</h3>
        <dl>
            <dt>Name</dt>
            <dd>Jonai Serrano</dd>
            <dt>Born</dt>
            <dd>1999</dd>
            <dt>Birthplace</dt>
            <dd>California</dd>
            <dt>Color</dt>
            <dd>Purple</dd>
        </dl>

        <pre><code>
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
        </code></pre>

        <pre><code>
The final element.
        </code></pre>
    </div>

    <footer>
        <p>&copy; 2024 My Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>
