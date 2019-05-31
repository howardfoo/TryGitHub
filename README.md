# TryGitHub
while IFS= read -r abc.txt; do
    echo "Text read from file: $1"
done < "$1"
