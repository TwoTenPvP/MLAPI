---
title: OnClientLoadedSceneDelegate
name: OnClientLoadedSceneDelegate
permalink: /api/on-client-loaded-scene-delegate/
---

<div style="line-height: 1;">
	<h2 markdown="1">OnClientLoadedSceneDelegate ``class``</h2>
	<p style="font-size: 20px;"><b>Namespace:</b> MLAPI.SceneManagement</p>
	<p style="font-size: 20px;"><b>Assembly:</b> MLAPI.dll</p>
</div>
<p>Delegate type for when a client is done loading the scene.</p>

<div>
	<h3 markdown="1">Inherited Properties</h3>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``MethodInfo`` Method { get; }</b></h4>
		<h5 markdown="1">Inherited from: ``Delegate``</h5>
	</div>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``object`` Target { get; }</b></h4>
		<h5 markdown="1">Inherited from: ``Delegate``</h5>
	</div>
</div>
<br>
<div>
	<h3>Public Constructors</h3>
	<div style="line-height: 1; ">
		<h4 markdown="1"><b>public [``OnClientLoadedSceneDelegate``](/MLAPI/api/on-client-loaded-scene-delegate/)(``object`` object, ``IntPtr`` method);</b></h4>
	</div>
		<h5><b>Parameters</b></h5>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``object`` object</p>
		</div>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``IntPtr`` method</p>
		</div>
</div>
<br>
<div>
	<h3 markdown="1">Public Methods</h3>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``void`` Invoke(``ulong`` clientId);</b></h4>
		<h5><b>Parameters</b></h5>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``ulong`` clientId</p>
		</div>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``IAsyncResult`` BeginInvoke(``ulong`` clientId, ``AsyncCallback`` callback, ``object`` object);</b></h4>
		<h5><b>Parameters</b></h5>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``ulong`` clientId</p>
		</div>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``AsyncCallback`` callback</p>
		</div>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``object`` object</p>
		</div>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``void`` EndInvoke(``IAsyncResult`` result);</b></h4>
		<h5><b>Parameters</b></h5>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``IAsyncResult`` result</p>
		</div>
	</div>
	<br>
</div>
<br>
<div>
	<h3 markdown="1">Inherited Methods</h3>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``void`` GetObjectData(``SerializationInfo`` info, ``StreamingContext`` context);</b></h4>
		<h5 markdown="1">Inherited from: ``MulticastDelegate``</h5>
		<h5><b>Parameters</b></h5>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``SerializationInfo`` info</p>
		</div>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``StreamingContext`` context</p>
		</div>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``bool`` Equals(``object`` obj);</b></h4>
		<h5 markdown="1">Inherited from: ``MulticastDelegate``</h5>
		<h5><b>Parameters</b></h5>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``object`` obj</p>
		</div>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``int`` GetHashCode();</b></h4>
		<h5 markdown="1">Inherited from: ``MulticastDelegate``</h5>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``Delegate[]`` GetInvocationList();</b></h4>
		<h5 markdown="1">Inherited from: ``MulticastDelegate``</h5>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``object`` DynamicInvoke(``object[]`` args);</b></h4>
		<h5 markdown="1">Inherited from: ``Delegate``</h5>
		<h5><b>Parameters</b></h5>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``object[]`` args</p>
		</div>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``object`` Clone();</b></h4>
		<h5 markdown="1">Inherited from: ``Delegate``</h5>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``Type`` GetType();</b></h4>
		<h5 markdown="1">Inherited from: ``object``</h5>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``string`` ToString();</b></h4>
		<h5 markdown="1">Inherited from: ``object``</h5>
	</div>
</div>
<br>
