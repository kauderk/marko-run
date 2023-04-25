Executing task: npm run build 


> netlify-example@0.0.1 build
> marko-run build

┌────────┬──────┬─────────────────┬────┬──────┬───────────┐
│ METHOD │ PATH │ ENTRY           │ MW │ META │ SIZE/GZIP │
├────────┼──────┼─────────────────┼────┼──────┼───────────┤
│ GET    │ /    │ handler -> page │  1 │  ✓   │    0.0 kB │
│ POST   │      │ handler         │  1 │  ✓   │           │
│ PUT    │      │ handler         │  1 │  ✓   │           │
│ DELETE │      │ handler         │  1 │  ✓   │           │
│ *      │ 404  │ page            │    │      │    0.0 kB │
│ *      │ 500  │ page            │    │      │    0.0 kB │
└────────┴──────┴─────────────────┴────┴──────┴───────────┘

  netlify\edge-functions\index.js  120.1kb

Done in 23ms
 *  Terminal will be reused by tasks, press any key to close it. 

 *  Executing task: npm run start 


> netlify-example@0.0.1 start
> marko-run preview

┌────────┬──────┬─────────────────┬────┬──────┬───────────┐
│ METHOD │ PATH │ ENTRY           │ MW │ META │ SIZE/GZIP │
├────────┼──────┼─────────────────┼────┼──────┼───────────┤
│ GET    │ /    │ handler -> page │  1 │  ✓   │    0.0 kB │
│ POST   │      │ handler         │  1 │  ✓   │           │
│ PUT    │      │ handler         │  1 │  ✓   │           │
│ DELETE │      │ handler         │  1 │  ✓   │           │
│ *      │ 404  │ page            │    │      │    0.0 kB │
│ *      │ 500  │ page            │    │      │    0.0 kB │
└────────┴──────┴─────────────────┴────┴──────┴───────────┘

  netlify\edge-functions\index.js  97.5kb

Done in 20ms
node:events:491
      throw er; // Unhandled 'error' event
      ^

Error: spawn netlify ENOENT
    at ChildProcess._handle.onexit (node:internal/child_process:283:19)
    at onErrorNT (node:internal/child_process:476:16)
    at process.processTicksAndRejections (node:internal/process/task_queues:82:21)        
Emitted 'error' event on ChildProcess instance at:
    at ChildProcess._handle.onexit (node:internal/child_process:289:12)
    at onErrorNT (node:internal/child_process:476:16)
    at process.processTicksAndRejections (node:internal/process/task_queues:82:21) {      
  errno: -4058,
  code: 'ENOENT',
  syscall: 'spawn netlify',
  path: 'netlify',
  spawnargs: [
    'dev',
    '--framework',
    '#static',
    '--dir',
    'netlify',
    '--port',
    '3000'
  ]
}

Node.js v18.9.0

 *  The terminal process "C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe -Command npm run start" terminated with exit code: 1. 
 *  Terminal will be reused by tasks, press any key to close it. 
