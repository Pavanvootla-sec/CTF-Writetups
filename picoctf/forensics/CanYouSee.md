=>  Extract the folder
=>  Use exiftool to read metadata
Command: exiftool imagename.jpg
=> You will find this 
Attribution URL                 : cGljb0NURntNRTc0RDQ3QV9ISUREM05fYTZkZjhkYjh9Cg==
=> As we see it is base64 encoded.It can be decoded with this command 
echo"cGljb0NURntNRTc0RDQ3QV9ISUREM05fYTZkZjhkYjh9Cg==" | base64 -d

