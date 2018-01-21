# axel-clui
Interface between user/browser integration and axel CLI downloader

The download url is passed as first argument



It scans the download url for file extention and downloads the file properly inside one of the following folder inside ~/Downloads directory .


  Compressed - BIN|ZIP|GZ|7Z|XZ|Z|TAR|TGZ|BZ2|LZH|A[0-9]?|RAR|R[0-9][0-9]

  Documents - doc|pdf|ppt|pps|docx|pptx

  Music - mp3|wav|wma|mpa|ram|ra|aac|aif|m4a|ogg

  Programs - ISO|RPM|DEB|EXE|MSI|APK

  Video - avi|mpg|mpe|mpeg|asf|wmv|mov|qt|rm|mp4|flv|m4v|webm|ogv|mkv


And finally executes axel command inside new terminal window to download the file in proper subdirectory. 
