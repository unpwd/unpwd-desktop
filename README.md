## contributor

1. Clone the repository to your local
2. Init git submodule
   ```bash
   git submodule init
   ```
3. Update git submodule
   ```bash
   git submodule update --remote
   ```
4. Go to the `frontend` directory and install the dependencies
   ```bash
   cd frontend
   pnpm install
   cd ..
   ```
5. Next you're ready to develop
   
   Note that the `wails dev` or `wails build` command is executed with the `-s` parameter `wails dev -s`.

   For more details, please see: [https://wails.io/docs/guides/manual-builds/#cli-steps](https://wails.io/docs/guides/manual-builds/#cli-steps)
