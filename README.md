<h2>Overview</h2>
<p>This project is a multi-threaded proxy server implemented in C. It handles multiple concurrent client requests using semaphores and optimizes request processing with an LRU caching mechanism.</p>

<h2>Features</h2>
<ul>
    <li>Multi-threading support using pthreads.</li>
    <li>TCP-based communication for handling client-server requests.</li>
    <li>LRU-based caching mechanism to improve response time.</li>
    <li>Synchronization using semaphores for efficient concurrency management.</li>
    <li>Request filtering to control access to specific websites.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
    <li><strong>Programming Language:</strong> C</li>
    <li><strong>Networking:</strong> TCP sockets</li>
    <li><strong>Concurrency:</strong> pthreads, semaphores</li>
    <li><strong>Caching Algorithm:</strong> LRU (Least Recently Used)</li>
</ul>

<h2>Installation</h2>
<pre><code># Clone the repository

git clone https://github.com/your-repo/multi-threaded-proxy-server.git
cd multi-threaded-proxy-server

Build the project

make all

Run the proxy server

./proxy <port-number>

<h2>Usage</h2>
<ol>
    <li>Run the proxy server using the command mentioned above.</li>
    <li>Configure your browser to use <code>localhost:&lt;port-number&gt;</code> as the proxy.</li>
    <li>Access websites through the proxy and experience caching optimization.</li>
</ol>

<h2>Limitations</h2>
<ul>
    <li>Fixed cache size may not store large websites efficiently.</li>
    <li>The proxy currently supports only GET requests.</li>
</ul>

<h2>Future Improvements</h2>
<ul>
    <li>Implement support for POST requests.</li>
    <li>Add domain-based access restrictions.</li>
    <li>Enhance security with request encryption.</li>
</ul>

<h2>Contributing</h2>
<p>Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.</p>
