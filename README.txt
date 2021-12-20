Undistro component employing the Kubernetes go-client record package <k8s.io/client-go/tools/record>, ensuring the event recorder is only initialized once. Also implementing 2 functions from the go-client <record.EventRecorder> interface.

This is mainly used by the <meta> component from Undistro.
