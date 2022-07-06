<script>
	export default {
		onLaunch: function() {

		},
		onShow: function() {

		},
		onHide: function() {

		}
	}
</script>

<style>
	/*每个页面公共css */
	@font-face {
		font-family: "iconfont";
		/* Project id 3492117 */
		src: url('~@/static/iconfont/iconfont.woff2?t=1656559687290') format('woff2'),
			url('~@/static/iconfont/iconfont.woff?t=1656559687290') format('woff'),
			url('~@/static/iconfont/iconfont.ttf?t=1656559687290') format('truetype');
	}

	.iconfont {
		font-family: "iconfont" !important;
		font-size: 16px;
		font-style: normal;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
	}

	.icon-shouye:before {
		content: "\e62d";
	}

	.icon-fangdajing:before {
		content: "\e60b";
	}

	.icon-icon:before {
		content: "\e6a0";
	}

	.icon-yousanjiao:before {
		content: "\e629";
	}

	.icon-guanbi:before {
		content: "\e6cc";
	}

	.icon-bofang:before {
		content: "\e624";
	}

	.icon-zanting:before {
		content: "\e62a";
	}

	.icon-bofang_o:before {
		content: "\eb5e";
	}

	.icon-dianzan:before {
		content: "\ec7f";
	}

	.icon-zuojiantou:before {
		content: "\e60c";
	}

	.icon-fenxiang:before {
		content: "\e601";
	}

	.container {
		width: 100%;
		height: calc(100vh - 70px);
		overflow: hidden;
	}

	.container scroll-view {
		height: 100%;
	}

	.fixbg {
		width: 100%;
		height: 100vh;
		position: fixed;
		left: 0;
		top: 0;

		background-size: cover;
		background-position: center 0;
		filter: blur(20px);
		transform: scale(1.2);
	}
</style>
