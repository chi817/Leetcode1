# Leetcode1

<pre class="language-sql"><code class="lang-sql"><strong>##1873. Calculate Special Bonus
</strong><strong>select employee_id,
</strong>case when employee_id%2=1 and name not like 'M%' then salary
else 0 end as bonus
from Employees
order by employee_id
</code></pre>
