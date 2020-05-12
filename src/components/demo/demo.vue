<script>
import demoHtml from './demo.html'
import methods from './methods'

export default {
  extends: demoHtml,
  data () {
    return {
      data: null
    }
  },
  methods: {
    get: methods.get
  }
}
</script>
