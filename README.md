# File-Upload-using-HTML-and-JS![uploadfile](https://user-images.githubusercontent.com/58586792/204757120-8376525a-2918-46bd-8d42-14e3bfbcf3b1.PNG)

To create an user interface for user file input or to upload a file for further process like file conversion, file modification, to read or write files is bit of struggle. HTML and JS combined made this process look easy.

### HTML <input> Tag
<input> tag with type="file" is used for browsing and uploading the file
              <input type="button" class="uploadButton" value="Browse" />
              <input type="file" name="upload" accept="image/*" id="fileUpload" />
              <input type="button" class="uploadButton" value="Upload File" />
              
### JS function 
              $('input[type=file]').change(function (e) {
                          $in = $(this);
                          $in.next().html($in.val());

                      });
