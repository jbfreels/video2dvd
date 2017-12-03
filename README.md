# video2dvd
Convert video to DVD (save ISO or burn DVD)

The plan is, to merge the iso creation and DVD burning.  Offer convenient options to burn the ISO, eject the DVD, etc..

## execute
```bash
$ video2dvd my_video.mp4 
$ cdrecord -v dev=/dev/sr0 <iso_path>
```

## TODO
- [ ] check for device in mtab  
- [ ] eject option  
- [ ] iso output option  
- [ ] PAL/NTSC support  
- [ ] ffmpeg aspect ratio support
- [X] file processing in tmp filder
- [ ] cleanup TMP_PATH