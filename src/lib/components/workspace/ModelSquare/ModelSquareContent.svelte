<script>

</script>


<main class="model-square-content">
	<div class="empty-page">
		<div class="empty-page-banner">
			<img src="src/lib/images/bg-create-cb72615c.png" alt="bg-create-cb"
				style="height: 84px; margin-left: 20%; margin-top: 69px"
			>
			<p class="empty-text">低门槛领域精调，全栈工具链加速大模型效果定制</p>
			<div class="empty-button">
				<span class="data-track-btn">
					<img src="src/lib/images/one-sentence-fintune-3fed0cdc.png" alt="fintune" style="width: 210px; height: 48px; padding-right: 20px">
				</span>
				<span class="data-track-btn">
					<img src="src/lib/images/deep-fintune-b8225b3c.png" alt="fintune" style="width: 118px; height: 48px">
				</span>
			</div>
		</div>

		<div class="hot-model-outer-wrapper">
			<div class="hot-model">
				<div class="left-model-classify-wrapper">
					<div class="left-model-classify-detail">
						<div class="ant-spin-nested-loading">
							<div class="ant-spin-container">
								<div class="top-category-wrapper">
									<div class="top-category-title" style="margin-top: 0px;">模型类别</div>
									<div title="文本生成" class="second-category-wrapper ell">文本生成</div>
									<div title="图像分类" class="second-category-wrapper ell">图像分类</div>
									<div title="文生图" class="second-category-wrapper ell">文生图</div>
								</div>
								<div class="top-category-wrapper">
									<div class="top-category-wrapper">
										<div class="top-category-title" style="margin-top: 24px;">模型场景</div>
										<div title="代码" class="second-category-wrapper ell">代码</div>
										<div title="逻辑推理" class="second-category-wrapper ell">逻辑推理</div>
										<div title="内容创作" class="second-category-wrapper ell">内容创作</div>
										<div title="对话" class="second-category-wrapper ell">对话</div>
										<div title="数学" class="second-category-wrapper ell">数学</div>
										<div title="指令遵循" class="second-category-wrapper ell">指令遵循</div>
										<div title="人格" class="second-category-wrapper ell">人格</div>
										<div title="摘要" class="second-category-wrapper ell">摘要</div>
										<div title="知识问答" class="second-category-wrapper ell">知识问答</div>
									</div>
								</div>
								<div class="top-category-wrapper">
									<div class="top-category-wrapper">
										<div class="top-category-title" style="margin-top: 24px;">语言支持</div>
										<div title="中文" class="second-category-wrapper ell">中文</div>
										<div title="多语言" class="second-category-wrapper ell">多语言</div>
										<div title="英文" class="second-category-wrapper ell">英文</div>
									</div>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>

			<div class="home-page-model-hot">
				<div class="model-list-top-filter-tool">
					<div class="maas-input">
						<span class="ant-input-affix-wrapper css-cp33m2 ant-input-outlined">
							<span class="ant-input-prefix" style="display: inline-block">
								<img src="src/lib/images/searchicon.png" alt="search-icon">
							</span>
							<input placeholder="请输入模型名称" class="ant-input css-cp33m2" type="text" value="">
							<span class="ant-input-suffix"></span>
						</span>
					</div>
					<div class="maas-segmented-wrapper"></div>
				</div>
				<div class="model-list-top-filter-result"></div>
				<div class="ant-spin-nest-loading"></div>
			</div>
		</div>
	</div>

</main>


<style>
	.empty-page-banner {
			width: 100%;
			height: 364px;
			background-color: #9ca3af;
			/*position: absolute;*/
			/*left: 2px;*/
			overflow: hidden;
	}
	.empty-page .empty-page-banner .empty-text {
    margin-top: 20px;
    margin-left: 20%;
    font-size: 16px;
    /*font-family: PingFang SC, PingFang SC-Regular;*/
    font-weight: 400;
    color: #1f2434bf;
    line-height: 22px;
    letter-spacing: .4px;
}
	.empty-button {
			width: 1185px;
			height: 120px;
			margin-left: 296px;
	}
	img {
    overflow-clip-margin: content-box;
    overflow: clip;
	}
	.empty-page .empty-page-banner .empty-button img {
    border-radius: 40px;
    cursor: pointer;
	}
	.empty-page .empty-page-banner img {
    margin-top: 69px;
	}

	.data-track-btn {
			display: inline-block;
	}

	.hot-model-outer-wrapper {
			width: auto;
			height: 2972px;
	}

	/*右侧白实线*/
	/*.empty-page .hot-model .left-model-classify-wrapper {*/
	/*	border-right: 1px solid rgba(226, 232, 255, .5);*/
	/*}*/

	.empty-page .hot-model .left-model-classify-wrapper {
    border-right: 1px solid rgba(226, 232, 255, .5);
	}


	.ant-spin-container {
    position: relative;
    transition: opacity 0.3s;
	}

	.top-category-title {
      font-size: 16px;
      font-weight: 500;
      color: #111928;
      line-height: 19px;
      margin-bottom: 16px;
      padding: 0 10px;
      margin-right: 12px;
  }
	.second-category-wrapper {
    padding: 0 10px;
    margin-right: 12px;
    font-size: 14px;
    cursor: pointer;
    user-select: none;
    font-weight: 400;
    color: #00000080;
    line-height: 28px;
    height: 28px;
    margin-bottom: 12px;
	}
	.ell {
    white-space: nowrap;
    text-overflow: ellipsis;
    overflow: hidden;
	}
	/*.hot-model {*/
	/*		width: 197px;*/
	/*		height: 1908px;*/
	/*		background-color: #d1d5db;*/
	/*}*/
	.hot-model {
    width: 100%;
    padding: 32px 40px;
    background: #ffffff;
    border-radius: 16px;
    display: grid
;
    grid-template-columns: 198px 1fr;
}
	/*.hot-model-outer-wrapper {*/
	/*		position: relative;*/
	/*		top: 2px;*/
	/*		background-color: #0d1117;*/
	/*		border-radius: 5px;*/
	/*}*/
</style>