```
    <div :class="`${name}-application-scenarios`">

      <div
          :class="`${name}-application-scenarios-person`"
          v-for="(item, index) in vdhLoopImgs"
          :key="index"
          v-show="vdhLoopNum === index"
        >
          <img :src="item" alt="" />
          <!-- <img v-lazy="item" :key="item" alt=""> -->
        </div>
        <div :class="`${name}-ulli`">
          <ul>
            <li
              v-for="(item, index) in vdhLoopImgs"
              :key="index"
              :class="vdhLoopNum === index ? 'virtual-digital-human-ulli-active' : ''"
            ></li>
          </ul>
        </div>
    </div>
```