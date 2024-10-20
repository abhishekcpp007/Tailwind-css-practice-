step 1- Run the following commands
npm install -D tailwindcss
npx tailwindcss init

step 2-
Open the tailwind.config.js 

content:["*.html"]

step 3-
create src/input.css to  include
@tailwind base;
    @tailwind components;
    @tailwind utilities;

step4-
run the following command
include the src/output.css file to your html

step 5-
run the following command

npx tailwindcss -i ./src/input.css -o ./src/output.css --watch

