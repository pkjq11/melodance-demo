<script setup>
</script>

<template>
  <div>
    <el-divider />

    <el-row justify="center">
      <h1 class="section-title">Explainer Video</h1>
    </el-row>

    <!-- 每个网站的视频的iframe可能不一致，最好在这里手动调整 -->
    <el-row justify="center">
      <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="10" >
        <el-row>
          <el-col :span="12">
            <!-- local -->
            <el-container class="video-container">
              <video controls muted preload playsinline>
                <source src="/video/036.mp4" type="video/mp4">
              </video>
            </el-container>
          </el-col>
          <el-col :span="12">
            <!-- local -->
            <el-container class="video-container">
              <video controls muted preload playsinline>
                <source src="/video/120.mp4" type="video/mp4">
              </video>
            </el-container>
          </el-col>
          <el-col :span="12">
            <!-- local -->
            <el-container class="video-container">
              <video controls muted preload playsinline>
                <source src="/video/143.mp4" type="video/mp4">
              </video>
            </el-container>
          </el-col>
          <el-col :span="12">
            <!-- local -->
            <el-container class="video-container">
              <video controls muted preload playsinline>
                <source src="/video/130.mp4" type="video/mp4">
              </video>
            </el-container>
          </el-col>
        </el-row>
      </el-col>
    </el-row>
    <div v-space="20"></div>
    <el-row justify="center">
      <h1 class="section-title">Explainer Video in the Wild Music</h1>
    </el-row>

    <!-- 每个网站的视频的iframe可能不一致，最好在这里手动调整 -->
    <el-row justify="center">
      <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="10" >
        <el-row>
          <el-col :span="12">
            <!-- local -->
            <el-container class="video-container">
              <video controls muted preload playsinline>
                <source src="/video/GQ.mp4" type="video/mp4">
              </video>
            </el-container>
          </el-col>
          <el-col :span="12">
            <!-- local -->
            <el-container class="video-container">
              <video controls muted preload playsinline>
                <source src="/video/boyfriend.mp4" type="video/mp4">
              </video>
            </el-container>
          </el-col>
          <el-col :span="12">
            <!-- local -->
            <el-container class="video-container">
              <video controls muted preload playsinline>
                <source src="/video/fire.mp4" type="video/mp4">
              </video>
            </el-container>
          </el-col>
          <el-col :span="12">
            <!-- local -->
            <el-container class="video-container">
              <video controls muted preload playsinline>
                <source src="/video/fortnight.mp4" type="video/mp4">
              </video>
            </el-container>
          </el-col>
          <el-col :span="12">
            <!-- local -->
            <el-container class="video-container">
              <video controls muted preload playsinline>
                <source src="/video/fractures.mp4" type="video/mp4">
              </video>
            </el-container>
          </el-col>
          <el-col :span="12">
            <!-- local -->
            <el-container class="video-container">
              <video controls muted preload playsinline>
                <source src="/video/havana.mp4" type="video/mp4">
              </video>
            </el-container>
          </el-col>
        </el-row>
      </el-col>
    </el-row>
    <div v-space="20"></div>
    <el-row justify="center">
      <h1 class="section-title">Explainer Video for Dance consistency</h1>
    </el-row>
    <el-row justify="center">
      <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="10" >
        <el-row>
          <el-col :span="12">
            <!-- local -->
            <el-container class="video-container">
              <video controls muted preload playsinline>
                <source src="/video/fortnight_compare.mp4" type="video/mp4">
              </video>
            </el-container>
          </el-col>
          <el-col :span="12">
            <!-- local -->
            <el-container class="video-container">
              <video controls muted preload playsinline>
                <source src="/video/Havana_compare.mp4" type="video/mp4">
              </video>
            </el-container>
          </el-col>
        </el-row>
      </el-col>
    </el-row>
  </div>
</template>

<style scoped>

.video-container{
  margin: 20px 0px 0px 0px;
}

iframe, video {
  aspect-ratio: 16 / 9;
  width: 100%;
}

</style>
