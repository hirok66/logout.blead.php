# logout.blead.php
&lt;form method="POST" action="{{ route('logout') }}"  > @csrf &lt;a href="{{ route('logout') }}" class="nav-link" onclick="event.preventDefault();this.closest('form').submit();"> &lt;i data-feather="log-out">&lt;/i> &lt;span>Log Out&lt;/span> &lt;/a> &lt;/form>
