# learning_github

mkdir -p videos transcripts


rclone copy 'gdrive:Apna College/Sigma 8.0 (DSA with Java)/19' ./videos --progress --transfers 4

   
// For all file in the videos folder
python3 transcribe_one_by_one.py "videos/"
    
// For only single file inside videos folfer
python3 transcribe_one_by_one.py "videos/video_n.mp4