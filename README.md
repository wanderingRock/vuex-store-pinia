# vuex-store-pinia

### Why Pinia

Pinia (pronounced /piːnjʌ/, like "peenya" in English) is the closest word to piña (pineapple in Spanish) that is a valid package name. A pineapple is in reality a group of individual flowers that join together to create a multiple fruit. Similar to stores, each one is born individually, but they are all connected at the end. It's also a delicious tropical fruit indigenous to South America.

# Installation

```
npm install pinia
```

```
import { createApp } from 'vue'
import { createPinia } from 'pinia'
import App from './App.vue'

const pinia = createPinia()
const app = createApp(App)

app.use(pinia)
app.mount('#app')
```
# State
  預設狀態

# Getters
  可處理state裡面的數值
  也可直接retune

# Action
  可處理state裡面的數值
  可異步處理資料(async非同步函式,await 則可以將非同步的程式碼寫成類似同步的形式。),用api做串接
