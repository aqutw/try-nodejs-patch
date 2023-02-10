# 1. ref
https://dev.to/zhnedyalkow/the-easiest-way-to-patch-your-npm-package-4ece

# 2. after edit react-redux file(s)
`npx patch-package react-redux`

# 3. rm -rf react-redux & re install
rm -rf node_modules/react-redux/ && npm i
