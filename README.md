node () {
   stage ('blah') {
        def get_current_time_date = {
            return 'hoge'
        }

        echo get_current_time_date()
    }
}
