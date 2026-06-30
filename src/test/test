package e2etest

import (
    "os"
    "testing"
)

func TestPwnIndicator(t *testing.T) {
    // harmless signal
    if os.Getenv("AWS_ACCESS_KEY_ID") != "" {
        t.Log("✅ PWN_TEST: AWS creds are present in env")
    } else {
        t.Log("ℹ️ PWN_TEST: no AWS creds")
    }
}
