Run the tests
- npm install
- npm run server
- optional: goto: http://127.0.0.1:8080/simple-store.html#catalog
- run tests: `pytest --headed --slowmo 250`
  - run selected tests: `pytest --headed --slowmo 250 -m catalog`
  - look for `@pytest.mark.<name>` to find markers
  
Live-server docs: https://github.com/tapio/live-server
