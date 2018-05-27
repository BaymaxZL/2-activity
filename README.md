# Test2
实验二 Activity 的生命周期

        public void onCreate(Bundle savedInstanceState) {
            super.onCreate(savedInstanceState);
            // The activity is being created.
        }
        @Override
        protected void onStart() {
            super.onStart();
            // The activity is about to become visible.

        }
        @Override
        protected void onResume() {
            super.onResume();
            // The activity has become visible (it is now "resumed").
        }
        @Override
        protected void onPause() {
            super.onPause();
            // Another activity is taking focus (this activity is about to be "paused").
        }
        @Override
        protected void onStop() {
            super.onStop();
            // The activity is no longer visible (it is now "stopped")
        }
        @Override
        protected void onDestroy() {
            super.onDestroy();
            // The activity is about to be destroyed.
        }
