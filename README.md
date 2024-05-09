Monorepo setup From youtube: // https://www.youtube.com/watch?v=Lam0cYOEst8

When cloning the repository to another machine, remember to clone recursively to include the content of submodules:
git clone --recursive https://github.com/yourusername/bookstore-monorepo.git

If you clone without --recursive, you'll need to fetch submodule content manually:
git submodule update --init --recursive
