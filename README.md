# caesium

Dockerfile for https://github.com/Lymphatus/caesium-clt to circumvent issue https://github.com/Lymphatus/caesium-clt/issues/38 

Small update to https://github.com/bardiir/caesium/   

Need to be careful of relative paths - so put converted folder inside main image folder.

sudo docker run -it -v /localimagefolder:/caesium dockerimage [e.g. sandywilkinson/caesium]

caesiumclt -q 30 -o compressimages *.jpg  [where compressimages is output folder and *.jpg represents jpgs within the current directory]
