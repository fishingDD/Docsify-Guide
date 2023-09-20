<p>【🎵被动】</p>
<audio controls="controls" class="record-audio" controls controlslist="nodownload  nofullscreen noremoteplayback">
<source src="./audio/被动.mp3" type="audio/mp3"></source>
</audio>
<p>【🎵红颜如霜】</p>
<audio controls="controls" class="record-audio" controls controlslist="nodownload  nofullscreen noremoteplayback">
<source src="./audio/红颜如霜.mp3" type="audio/mp3"></source>
</audio>
<p>【🎵夜曲】</p>
<audio controls="controls" class="record-audio" controls controlslist="nodownload  nofullscreen noremoteplayback">
<source src="./audio/夜曲.mp3" type="audio/mp3"></source>
</audio>
<p>【🎵敢爱敢做】</p>
<audio controls="controls" class="record-audio" controls controlslist="nodownload  nofullscreen noremoteplayback">
<source src="./audio/敢爱敢做.mp3" type="audio/mp3"></source>
</audio>
<p>【🎵暗号】</p>
<audio controls="controls" class="record-audio" controls controlslist="nodownload  nofullscreen noremoteplayback">
<source src="./audio/暗号.mp3" type="audio/mp3"></source>
</audio>
<script type="text/javascript">
			// 多个音频时播放一个
			const audios = document.getElementsByTagName("audio");
			// 暂停函数
			function pauseAll() {
				var self = this;
				[].forEach.call(audios, function(i) {
					// 将audios中其他的audio全部暂停
					i !== self && i.pause()
				})
			}
		 // 给play事件绑定暂停函数
         ;
			[].forEach.call(audios, function(i) {
				i.addEventListener('play', pauseAll.bind(i))
			})
</script>
