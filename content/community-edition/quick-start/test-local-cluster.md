---
date: 2016-03-09T00:11:02+01:00
title: Test Local Cluster
weight: 7
---

After [creating a local cluster](/community-edition/quick-start/create-local-cluster/), follow the instructions below to test its CQL and Redis services.


<ul class="nav nav-tabs">
  <li class="active">
    <a data-toggle="tab" href="#docker">
      <i class="fa fa-docker" aria-hidden="true"></i>
      <b>Docker</b>
    </a>
  </li>
  <li >
    <a data-toggle="tab" href="#macos">
      <i class="fa fa-apple" aria-hidden="true"></i>
      <b>macOS</b>
    </a>
  </li>
  <li>
    <a data-toggle="tab" href="#linux">
      <i class="fa fa-linux" aria-hidden="true"></i>
      <b>Linux</b>
    </a>
  </li>
</ul>

<div class="tab-content">
  <div id="docker" class="tab-pane fade in active">
    {{% includeMarkdown "community-edition/quick-start/docker/test-local-cluster.md" /%}}
  </div>
  <div id="macos" class="tab-pane fade">
    {{% includeMarkdown "community-edition/quick-start/binary/macos-test-local-cluster.md" /%}}
  </div>
  <div id="linux" class="tab-pane fade">
    {{% includeMarkdown "community-edition/quick-start/binary/linux-test-local-cluster.md" /%}}
  </div> 
</div>