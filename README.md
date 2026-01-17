git checkout --orphan main
git rm -rf .
cat > README.md <<'EOF'
Daedalus Gate - Memory MVP
EOF
git add README.md
git commit -m "chore: initial commit (create main branch)"
git push origin main
