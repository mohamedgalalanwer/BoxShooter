using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class BasicMover : MonoBehaviour {

    public float spinSpeed = 180.0f;
    public float motionMagnitude = 0.1f;
    public bool spin = true;
    public bool motion = false;

	
	// Update is called once per frame
	void Update () {
        if (spin) {
            gameObject.transform.Rotate (Vector3.up * spinSpeed * Time.deltaTime);
        }
        if (motion) {
            gameObject.transform.Translate (Vector3.up * Mathf.Cos (Time.timeSinceLevelLoad) * motionMagnitude);
        }
	}
}
