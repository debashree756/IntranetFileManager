# Tiny PHP File Manager
It is a simple, fast and small file manager with single php file. It is also a web code editor. It'll run either online or locally, on Linux, Windows or Mac based platforms. The only requirement is to have PHP 5.5+ available.

## Demo
<a href="https://tinyfilemanager.herokuapp.com" target="_blank">tinyfilemanager.herokuapp.com</a>

 Login Details : admin/admin | user/12345


## Documents
<a href="https://tinyfilemanager.github.io/" target="_blank">tinyfilemanager.github.io</a>
<hr>

<img src="screenshot.gif" alt="H3K | Tiny File Manager">

## Requirements

- PHP 5.5.0 or higher.
- [Zip extension](http://php.net/manual/en/book.zip.php) for zip and unzip actions.
- Fileinfo, iconv and mbstring extensions are strongly recommended.

## How to use

Download ZIP with latest version from master branch.

Copy tinyfilemanager.php to your website folder and open it with web browser (e.g. http://yoursite/any_path/tinyfilemanager.php).

Default username/password: admin/admin and user/12345.

Warning: Please set your own username and password in $auth_users before use. password is encrypted with <code>password_hash()</code>. to generate new password hash <a href="https://tinyfilemanager.github.io/docs/pwd.html" target="_blank">here</a>

To enable/disable authentication set $use_auth to true or false.

### Supported constants:

- `FM_ROOT_PATH` - default is `$_SERVER['DOCUMENT_ROOT']`
- `FM_ROOT_URL` - default is `'http(s)://site.domain/'`
- `FM_SELF_URL` - default is `'http(s)://site.domain/' . $_SERVER['PHP_SELF']`
- `FM_ICONV_INPUT_ENC` - default is `'CP1251'`
- `FM_USE_HIGHLIGHTJS` - default is `true`
- `FM_HIGHLIGHTJS_STYLE` - default is `'vs'`
- `FM_DATETIME_FORMAT` - default is `'d.m.y H:i'`
- `FM_EXTENSION` - default is `""` //upload files extensions


### :loudspeaker: Features 
<ul>
<li>:cd: Open Source, light and extremely simple</li>
<li>:information_source: Basic features likes Create, Delete, Modify, View, Download, Copy and Move files </li>
<li>:arrow_double_up: Ajax Upload, Ability to drag & drop, multiple files upload and file extensions filter </li>
<li>:file_folder: Ability to create folders and files</li>
<li>:gift: Ability to compress, extract files</li>
<li>:sunglasses: Support user permissions - based on session and each user root folder mapping</li>
<li>:floppy_disk: Copy direct file URL</li>
<li>:pencil2: Edit text formats file using advanced editor</li>
<li>:page_facing_up: Google Drive viewer helps you preview PDF/DOC/XLS/PPT/etc. 25 MB can be previewed with the Google Drive viewer</li>
<li>:zap: Backup files</li>
<li>:mag_right: Search -  Search and Sorting using datatable js</li>
<li>:file_folder: Exclude folders from listing</li>
<li>:bangbang: lots more...</li>
</ul>

###### CDN Used

 `jQuery | Bootstrap | Font Awesome | Highlight js | ace js | DropZone js | DataTable js`
