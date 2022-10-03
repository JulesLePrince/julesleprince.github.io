# Global Overview
### What is it?
Alfred is a torrent searcher and a torrent streaming service. It means that with a given movie, Alfred will find the best torrent on an indexer website and will stream it so that you can watch it directly. <br /> Here is a short demo in order to understand how it works : 


<video src="https://user-images.githubusercontent.com/31992334/193637801-6d718e49-38f6-4606-9d54-1042fd0e914b.mov" controls="controls" style="max-width: 730px;">
</video>

A lot is going on!! Let's dive in and explain what happened: 
* First the user have to select a movie giving a TheMovieDataBase id that will be used for metadata.
* The TMDB id is send to a server which finds the best movie torrent file on an indexer website and streams it through webtorrent. The streaming url is sent back to the user machine.
* Once The user machine received the url of the torrent streaming movie, it launches it in IINA(a macOS video viewer)
