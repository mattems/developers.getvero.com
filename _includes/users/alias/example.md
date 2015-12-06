### Definition

<pre class="bash"><code>POST 'https://api.getvero.com/api/v2/users/reidentify'</code></pre>
<pre class="ruby"><code>Vero::Customers.alias</code></pre>

### Example request

<pre class="bash"><code>curl 'https://api.getvero.com/api/v2/users/reidentify' \
  -d 'auth_token=AUTH_TOKEN' \
  -d 'id=123' \
  -d 'new_id=456'</code></pre>
<pre class="ruby"><code>Vero::Customers.alias({id: 123, new_id: 'ABC-123'})</code></pre>