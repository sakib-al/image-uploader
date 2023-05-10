# Description
This is a small package for Image uploader. You can upload multiple image, single image or upload any files within it. Just link the css and js file in your Markup file.

## Installation Process

```bash
<link rel="stylesheet" href="assets/image-uploader.min.css">
<script src="assets/image-uploader.min.js"></script>
<script>
      $('.file').imageUploader();
  </script>
```


## Add a class in your <div>
  
 ```bash
  <div class="file"></div>
 ```
 
 ## Uploader Options
  
 ```bash
  <script>
      $('.file').imageUploader({
          required: false,
          multiple:true,
          imagesInputName: "test_file",
          label: 'This is a test label'
          icon: 'fa fa-cloud-upload'
      });
  </script>
 ```
