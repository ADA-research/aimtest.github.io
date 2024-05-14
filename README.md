# AIM-website
Website of the Chair for AI Methodology at RWTH Aachen University

## How to Update and Upload the Website

Steps for compiling the website locally and uploading it to the NAS

### Compiling locally with Jekyll
1. Ensure [Jekyll](https://jekyllrb.com) is installed. If not, install it by following their [official guide](https://jekyllrb.com/docs/installation/).
2. Clone this repository to your local machine.
3. Open a terminal and navigate to `AIM-website/jekyll`.
4. **Compile & Serve the Website**:
   1. Open a terminal and navigate to `AIM-website/jekyll`.  
   2. Run the following command: `bundle exec jekyll serve`
5. Once the server starts, you'll be provided with a local address (typically `http://127.0.0.1:4000/`). Open this address in your web browser to view your local version of the website.

### Updating the Website Online
6. Navigate to the 'web' folder located on the NAS (ask an admin to get access if you don't have it
yet)
7. Copy and paste the contents from the `_site` directory (your local compiled version) into the 'web' folder on the NAS. Make sure you only transfer the content inside `_site` and not the directory itself.
