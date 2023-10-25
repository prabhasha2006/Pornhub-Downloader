# Pornhub-Downloader

# INSTALLATION

First you should install the npm puppeteer

    npm install puppeteer

Require pornhub downloader plugin

    const { evelocode_pornhubdl } = require('./pornhub')

Parse your url and get result

    evelocode_pornhubdl('https://www.pornhub.com/view_video.php?viewkey=63d7d*******')
    .then(result => {
        console.log(result)
    })

Your outpot likes below

    {
      q1080: 'https://pr892d8.9xbud.com/hls/Y*****-+Pornhub_com_1080',
      q720: 'https://pr892d8.9xbud.com/hls/YT*****-+Pornhub_com_720',
      q480: 'https://pr892d8.9xbud.com/hls/YT*****-+Pornhub_com_480',      
      q240: 'https://pr892d8.9xbud.com/hls/YT*****-+Pornhub_com_240',      
      title: 'THE VIDEO TITLE',
      company: 'evelocode',
      downloader_by: 'Kumuthu Prabhasha'
    }
