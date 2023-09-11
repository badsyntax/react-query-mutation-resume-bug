# React Query Offline Resume Bug Repo

1. `npm install`
2. `npm run dev`
3. Visit <http://localhost:5173/1>
4. Go offline 
5. Add some comments
6. Refresh the page
7. Verify you have >0 pending migrations
8. Go online
9. Pending mutations are not sent (here's the bug)
10. Refresh the page
11. Pending mutations are now sent

