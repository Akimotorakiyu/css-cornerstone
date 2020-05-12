<template>
  <div class="home">
    <input type="text" />
    <span>你好世界你好世界你好世界你好世界你好世界你好世界你好世界你好世界你好世界你好世界你好世界你好世界你好世界你好世界</span>
    <input type="search" name id />
    <button>一钮</button>
    <button>一钮</button>
    <span>你好世界你好世界你好世界你好世界你好世界你好世界你好世界你好世界你好世界你好世界你好世界你好世界你好世界你好世界</span>
    <span>你好世界</span>
    <img src="//www.baidu.com/img/pc_906bd0e6235b67bd693484209bb70b29.gif" alt srcset />
    <select>
      <option>1</option>
      <option>3</option>
      <option>2</option>
    </select>
    <div>
      <input name="name" type="radio" />输入
       <input name="name" type="radio" /> <input name="name" type="radio" />输入
    </div>
    <div>
      <input name="name" type="checkbox" />
      <input name="name" type="checkbox" />
    </div>
    <div>
      <input name="name" type="checkbox" class="switch" v-model="show" />
      开关
    </div>

    <div class="dropdown" v-show="show">
      <h2>你好世界</h2>
      <h2>大家好菜是真的好</h2>
      <h2>天天向上</h2>
    </div>

    <div>1</div>
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {},
  data() {
    return {
      show: false
    };
  }
};
</script>
