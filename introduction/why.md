## 為什麼要使用 Docker？
作為一種新興的虛擬化方式，Docker 跟傳統的虛擬化方式相比具有眾多的優勢。

首先，Docker 容器的啟動可以在秒級實現，這相比傳統的虛擬機方式要快得多。
其次，Docker 對系統資源的利用率很高，一台主機上可以同時運行數千個 Docker 容器。

容器除了運行其中應用外，基本不消耗額外的系統資源，使得應用的性能很高，同時系統的開銷儘量小。傳統虛擬機方式運行 10 個不同的應用就要起 10 個虛擬機，而 Docker 只需要啟動 10 個隔離的應用即可。

具體說來，Docker 在如下幾個方面具有較大的優勢。

### 更快速的交付和部署
對開發和維運（develop）人員來說，最希望的就是一次建立或配置，可以在任意地方正常運行。

開發者可以使用一個標準的鏡像來構建一套開發容器，開發完成之後，維運人員可以直接使用這個容器來部署代碼。
Docker 可以快速創建容器，快速迭代應用程序，並讓整個過程全程可見，使團隊中的其他成員更容易理解應用程序是如何創建和工作的。
Docker 容器很輕很快！容器的啟動時間是秒級的，大量地節約開發、測試、部署的時間。

### 更高效的虛擬化
Docker 容器的運行不需要額外的虛擬化支持，它是內核級的虛擬化，因此可以實現更高的性能和效率。

### 更輕鬆的遷移和擴展

Docker 容器幾乎可以在任意的平台上運行，包括物理機、虛擬機、公有雲、私有雲、個人電腦、伺服器等。
這種兼容性可以讓用戶把一個應用程序從一個平台直接遷移到另外一個。

### 更簡單的管理
使用 Docker，只需要小小的修改，就可以替代以往大量的更新工作。所有的修改都以增量的方式被分發和更新，從而實現自動化並且高效的管理。

### 對比傳統虛擬機總結

| 特性 | 容器 | 虛擬機 |
| ---- | ---- | ------ |
| 啟動 | 秒級 | 分鐘級 |
| 硬碟容量 | 一般為 MB | 一般為 GB |
| 性能 | 接近原生 | 比較慢 |
| 系統支持量 | 單機支持上千個容器 | 一般幾十個 |
