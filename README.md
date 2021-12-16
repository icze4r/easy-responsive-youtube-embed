# easy-responsive-youtube-embed

blatantly, flagrantly stolen from https://flaviocopes.com/responsive-youtube-videos/ , but i've re-purposed it (can you even call it that) into a custom html element, so you just have to go videocontainer videoembed /videocontainer and you're done

in fact i don't even need to put more files than this here

here's what you do

put this in your css file or in the inline style tag:

        videocontainer { display: block; position: relative; padding-bottom: 56.25%; padding-top: 30px; height: 0; overflow: hidden; }

        videocontainer iframe, .video-container object, .video-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }
        left: 50%;
        transform: translate(-50%, -50%);
        }

okay, now get your youtube embed. put it in between the tags, like this

        <videocontainer>
        <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/MJ9E7yUR8TQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>
        </videocontainer>

bingo-bango! yer done, kid!
