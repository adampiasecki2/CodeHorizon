# Initialize Git repository (if not already initialized)
git init

# Create and commit 10 different files
for i in {1..10}; do
  echo "This is file $i" > "file$i.txt"
  git add "file$i.txt"
  git commit -m "Added file$i.txt"
done
