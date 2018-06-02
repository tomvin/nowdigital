Bundle the theme and it's sass files"
1. Inside the ThemeProject folder run:
npm run bundle

To compile and launch the style guide:

1. Install stylemark
npm install -g stylemark

2. Run stylemark from command line in the root directory
stylemark -i 'ThemeProject' -o 'StyleGuide' -w 2000 -b 8080 

3. This will generate a style guide for the ThemeProject, 
and launch it in your browser at http://localhost:8080