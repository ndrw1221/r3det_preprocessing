Preprocessing code for piglet tracking r3det model

Docker image with python 3.7 and opencv 4.1.0

## Usage:
Prepare volumes:
 - source : contains original pig video
 - cropped_frames : saves cropped frames
 - cropped_videos : saves cropped video
 - clips : saves clips for Sow Posture Recognition Model (SPRM)
~~~
docker run --rm -v source:/source \
				-v cropped_frames:/cropped_frames \
				-v cropped_videos:/cropped_videos \
				-v clips:/clips \
				crazyhathello/r3det_preprocessing
~~~

