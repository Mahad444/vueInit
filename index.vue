// Usage of VUe``
Vue.createApp({
    data:function() {
        return {
            goal: '',
            goals:[],
        }
    },
    methods: {
        addGoal() {
            console.log(this.goal)
            this.goals.push(this.goal)
            this.goal = ''
        }
    },
}).mount('#app')